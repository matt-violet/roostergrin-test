<template>
  <div class="container-fluid col-12">
    <div class="row align-items-center no-gutters">
      <div class="overlay col-12 offset-2">
        <h5>LOREM IPSUM</h5>
        <button>BUTTON BUTTON</button>
      </div>
      <img class="bg-img" src="../../assets/banner-1.jpg">
    </div>
  </div>
</template>

<script>
export default {
  name: "RowTwo",
}
</script>

<style scoped>
.overlay {
  position: absolute;
}
.bg-img {
  width: 100%;
}
h5 {
  color: rgb(133, 91, 172);
  font-weight: 600;
}
button {
  background: rgb(241, 133, 0);
  border: 0;
  color: white;
  font-size: 10px;
  font-weight: 700;
  padding: 10px;
  line-height: 15px;
}
/* -------------------------------- MEDIA QUERIES -------------------------------- */
@media (max-width: 576px) {
  h5 {
    font-size: 16px;
  }
  button {
    font-size: 8px;
    padding: 5px;
  }
}
@media (min-width: 577px) and (max-width: 992px) {
  h5 {
    font-size: 24px;
  }
}
@media (min-width: 993px) {
  h5 {
    font-size: 35px;
    margin-bottom: 15px;
  }
  button {
    font-size: 12px;
    padding: 15px;
  }
}
</style>
