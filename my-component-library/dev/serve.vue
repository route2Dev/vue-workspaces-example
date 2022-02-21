<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { MyComponentLibrarySample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  MyComponentLibrarySample,
  // }
});
</script>

<template>
  <div id="app">
    <my-component-library-sample />
  </div>
</template>
