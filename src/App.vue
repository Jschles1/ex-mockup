<template>
  <div id="app">
    <section class="hero">
      <navbar></navbar>
      <div class="container">
        <hero></hero>
      </div>
    </section>
    
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';

export default {
  components: {
    'navbar': Navbar,
    'hero': Hero
  }
}
</script>

<style lang="scss">
  #app {
    font-family: 'Open Sans', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  .hero {
    color: #fff;
    min-height: 750px;
    background: url(https://www.exodus.io/img/hero.jpg) center center;
    background-size: cover;
    text-align: center;
  }
</style>
