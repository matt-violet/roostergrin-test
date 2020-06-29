<template>
  <div class="home container-fluid col-12 no-gutters">
    <img
      class="logo col-2 offset-1"
      src="../../assets/logo-white.svg"
      @click="$emit('visitLink', false)"
    >
    <div class="row align-items-center">
      <div class="overlay col-7 offset-3">
        <h1 class="line-1">
          WELCOME TO
        </h1>
        <h1 class="line-2">
          Rooster Grin
        </h1>
        <button class="btn" @click="$emit('visitLink', false)">
          BUTTON BUTTON
        </button>
      </div>
      <img
        class="bg-img col-12"
        src="../../assets/hero.jpg"
      />
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
.logo:hover {
  cursor: pointer;
}
.overlay {
  text-align: center;
  position: absolute;
  color: white;
  padding: 0;
}
.line-1 {
  margin: 0;
  font-weight: 200;
}
.line-2 {
  font-weight: 600;
}
.btn {
  background: rgb(166, 112, 216);
  color: white;
  border: 0;
  font-size: 10px;
  font-weight: 700;
  line-height: 15px;
  margin-top: 8px;
  border-radius: 0;
  padding: 10px;
}
/* -------------------------------- MEDIA QUERIES -------------------------------- */
@media (max-width: 576px) {
  .line-1, .line-2 {
    font-size: 18px;
  }
  .logo {
    margin-left: 20px;
  }
  .btn {
    font-size: 7px;
    padding: 5px;
    margin: 0;
  }
}
@media (min-width: 577px) and (max-width: 768px) {
 .line-1, .line-2 {
    font-size: 30px;
  }
}
@media (min-width: 769px) and (max-width: 992px) {
  .line-1, .line-2 {
    font-size: 45px;
  }
}
@media (min-width: 993px) {
  .line-1, .line-2 {
    font-size: 60px;
  }
  .btn {
      font-size: 14px;
  }
}
</style>
