<template>
  <div>
    home page
    <v-html-panel src="1111"></v-html-panel>

  </div>
</template>

<script>
  import {mapModules, mapRules} from 'vuet'
  export default {
    mixins: [
      mapModules({self: 'user-self'}),
      mapRules({once: 'user-self'})
    ],
    name: 'index'
  }
</script>

<style scoped>

</style>
