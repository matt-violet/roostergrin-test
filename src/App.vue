<template>
  <div id="app" class="no-gutters">
    <Home @visitLink="handleLinkClick"/>
    <RowOne @visitLink="handleLinkClick"/>
    <RowTwo @visitLink="handleLinkClick"/>
    <RowThree @visitLink="handleLinkClick"/>
    <RowFour @visitLink="handleLinkClick"/>
    <RowFive/>
    <Footer @visitLink="handleLinkClick"/>
  </div>
</template>

<script>
import Home from "./components/Home.vue"
import RowOne from "./components/RowOne.vue"
import RowTwo from "./components/RowTwo.vue"
import RowThree from "./components/RowThree.vue"
import RowFour from "./components/RowFour.vue"
import RowFive from "./components/RowFive.vue"
import Footer from "./components/Footer.vue"

export default {
  name: "App",
  components: {
    Home,
    RowOne,
    RowTwo,
    RowThree,
    RowFour,
    RowFive,
    Footer,
  },
  methods: {
    handleLinkClick(url) {
      url ? window.open(url, '_blank') : alert('There doesn\'t seem to be anyhere else to go. Looks like you\'re stuck here... 🤓');
    }
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
button {
  transition: .5s !important;
}
button:hover {
  box-shadow: 5px 5px 10px black !important;
}
</style>
