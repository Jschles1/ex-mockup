<template>
  <div id="app">
    <section class="hero">
      <navbar></navbar>
      <div class="container">
        <hero></hero>
      </div>
    </section>
    <section class="intro">
      <intro></intro>
    </section>
    <section class="benefits">
      <benefits></benefits>
    </section>
    <section class="founders">
      <founders></founders>
    </section>
    <section class="features">
      <features></features>
    </section>
    <section class="problems">
      <problems></problems>
    </section>
    <section class="solution">
      <solution></solution>
    </section>
    <section class="download">
      <download></download>
    </section>
    <section class="scroll">
      <scroll></scroll>
    </section>
    <footer class="app-footer">
      <app-footer></app-footer>
    </footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Intro from './components/Intro.vue';
import Benefits from './components/Benefits.vue';
import Founders from './components/Founders.vue';
import Features from './components/Features.vue';
import Problems from './components/Problems.vue';
import Solution from './components/Solution.vue';
import Download from './components/Download.vue';
import Scroll from './components/Scroll.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    'navbar': Navbar,
    'hero': Hero,
    'intro': Intro,
    'benefits': Benefits,
    'founders': Founders,
    'features': Features,
    'problems': Problems,
    'solution': Solution,
    'download': Download,
    'scroll': Scroll,
    'app-footer': AppFooter
  }
}
</script>

<style lang="scss">
  body {
    line-height: 1.42857143;
  }

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
