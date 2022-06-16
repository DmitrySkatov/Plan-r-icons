<script>
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
import { PlanrIconsSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  components: {
   PlanrIconsSample,
  }
});
</script>

<template>
  <div id="app">
    <planr-icons-sample class-icon="Up" color="blue" font-size="14px" />
  </div>
</template>
