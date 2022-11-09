<template>
  <div class="container">
    <Navbar />
    <Politics />
    <Business />
    <Sports />
    <entartainment />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Politics from './components/politics.vue'
import Business from './components/business.vue'
import Sports from './components/sports.vue';
import Entartainment from './components/entartainment.vue';


export default {
  name: 'App',
  components: {
    Navbar,
    Politics,
    Business,
    Sports,
    Entartainment
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 55px;
}
</style>
