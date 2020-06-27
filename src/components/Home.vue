<template>
  <div class="home container col-12 no-gutters">
    <img class="logo col-2 offset-1" src="../../assets/logo-white.svg">
    <div class="row align-items-center">
      <div class="overlay col-5 offset-4">
        <h1 class="line-1">WELCOME TO</h1>
        <h1 class="line-2">Rooster Grin</h1>
        <button>BUTTON BUTTON</button>
      </div>
      <img class="bg-img col-12" src="../../assets/hero.jpg"/>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
}
</script>

<style scoped>
.bg-img {
  vertical-align: top;
  position: relative;
  z-index: -1;

}
.logo {
  position: absolute;
  margin-top: 25px;
}
.overlay {
  text-align: center;
  position: absolute;
  color: white;
}
.line-1 {
  margin: 0;
  font-size: 40px;
}
button {
  background: rgb(166, 112, 216);
  color: white;
  border: 0;
  font-size: 10px;
  line-height: 15px;
  padding: 10px 10px;
}
</style>
