<template>
  <div id="app" class="no-gutters">
    <Home/>
  </div>
</template>

<script>
import Home from "./components/Home.vue"

export default {
  name: "App",
  components: {
    Home
  }
}
</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
