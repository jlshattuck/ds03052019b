<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="./assets/logo.png"
    >
    <!-- <MelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Dashboard />
  </div>
</template>

<script>
import MelloWorld from './components/MelloWorld.vue'
import Dashboard from './components/Dashboard'
export default {
  name: 'app',
  components: {
    // MelloWorld,
    Dashboard
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
