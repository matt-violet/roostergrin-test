<template>
  <div id="app" class="no-gutters">
    <Home/>
    <RowOne/>
    <RowTwo/>
    <RowThree/>
    <RowFour/>
  </div>
</template>

<script>
import Home from "./components/Home.vue"
import RowOne from "./components/RowOne.vue"
import RowTwo from "./components/RowTwo.vue"
import RowThree from "./components/RowThree.vue"
import RowFour from "./components/RowFour.vue"

export default {
  name: "App",
  components: {
    Home,
    RowOne,
    RowTwo,
    RowThree,
    RowFour
  }
}
</script>

<style>
body {
  margin: 0;
}
html {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-weight: 200, 200, 400, 500, 600, 700, 800, 900;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  overflow: hidden;
}
</style>
