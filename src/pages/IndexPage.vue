<template>
  <q-page class="row items-center justify-evenly">
    <RawEditor />
  </q-page>
</template>

<script lang="ts">
import RawEditor from 'components/RawEditor.vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'IndexPage',
  components: { RawEditor },
  setup() {
    return {};
  },
});
</script>
