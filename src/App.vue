<template>
  <div id="app">
    <sidebar></sidebar>
  </div>
</template>

<script>
import sidebar from './components/sidebar.vue'

export default {
  name: 'app',
  components: {
    sidebar,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
