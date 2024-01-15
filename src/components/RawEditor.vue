<template>
  <div>
    <q-input v-model="text" filled type="textarea" />
  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'RawEditor',
  setup() {
    return {
      text: ref(''),
    };
  },
});
</script>
