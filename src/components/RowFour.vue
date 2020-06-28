<template>
  <div class="container-fluid col-12">
    <div class="row align-items-center no-gutters">
      <div class="overlay col-8 offset-2 col-sm-4 offset-sm-7 col-lg-4 col-xl-3 align-items-center">
        <h5>LOREM IPSUM</h5>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum odio eveniet alias itaque iusto tenetur qui, saepe, ab impedit, earum odit voluptatum quibusdam dignissimos dicta. Odio necessitatibus ducimus earum voluptates?</p>
        <button>BUTTON BUTTON</button>
      </div>
      <img class="bg-img" src="../../assets/banner-2.jpg">
    </div>
  </div>
</template>

<script>
export default {
  name: "RowFour",
}
</script>

<style scoped>
.bg-img {
  width: 100%;
}
h5 {
  color: rgb(133, 91, 172);
  font-size: 22px;
  font-weight: 700;
}
p {
  line-height: 1.2;
  font-size: 12px;
  margin-bottom: 15px;
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
  .bg-img {
    visibility: hidden;
    width: 0;
    height: 0;
  }
  .overlay {
    padding: 50px 0;
  }
}
@media (min-width: 577px) {
  .overlay {
    position: absolute;
  }
  h5 {
    font-size: 22px;
  }
  p {
    font-size: 11px; 
  }
}
@media (min-width: 769px) {
  h5 {
    font-size: 30px;
  }
  p {
    font-size: 14px;
  }
  button {
    font-size: 12px;
  }
}
@media (min-width: 992px) {
  h5 {
    font-size: 35px;
  }
  p {
    font-size: 16px;
    margin-bottom: 20px;
  }
  button {
    padding: 15px;
  }
}
</style>
