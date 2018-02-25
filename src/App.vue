<template>
  <div id="app">
    <navbar></navbar>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
export default {
  components: {
    'navbar': Navbar
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Open Sans', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
