<template>
  <div id="app">
    <FilePreviewer />
  </div>
</template>

<script>
import FilePreviewer from './views/file/FilePreviewer.vue'

export default {
  name: 'App',
  components: {
    FilePreviewer
  }
}
</script>

<style lang="css" scoped>
html {
  overflow-y: scroll;
  font-family: helvetica, arial, sans-serif;
}

body {
  margin: 0;
  padding: 0;
}
</style>
