<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Hero msg="Sound Ideas"/>
    <Services msg="Sound Ideas"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Hero from './components/Hero.vue'
import Services from './components/Services.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld,
    Hero,
    Services
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
}
</style>
