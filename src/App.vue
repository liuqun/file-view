<template>
  <div id="app">
    <HelloWorld msg="Welcome" />
    <FilePreviewer />
  </div>
</template>

<script>
import FilePreviewer from './views/file/FilePreviewer.vue'
import HelloWorld from './views/file/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
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
