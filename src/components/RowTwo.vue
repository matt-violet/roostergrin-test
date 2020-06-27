<template>
  <div class="row col-12 align-items-center no-gutters">
    <div class="overlay offset-2">
      <h5>LOREM IPSUM</h5>
      <button>BUTTON BUTTON</button>
    </div>
    <img class="bg-img" src="../../assets/banner-1.jpg">
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
    font-size: 14px;
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
    font-size: 32px;
  }
  button {
    font-size: 12px;
  }
}
</style>
