<template>
  <div class="row col-12 align-items-center no-gutters">
    <div class="left col-6">
      <div class="text">
        <h5>LOREM IPSUM</h5>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nulla alias iste assumenda labore repellendus a vitae unde ullam consectetur, nemo repudiandae rerum deleniti facilis, explicabo eos dicta quaerat voluptatum temporibus!</p>
        <a href="">> Lorem Ipsum</a>
      </div>
    </div>
    <div class="col-6 right">
      <img src="../../assets/img-1.jpg">
    </div>
  </div>
</template>

<script>
export default {
  name: "RowOne",
}
</script>

<style scoped>
.left {
  display: inline-block;
  padding: 30px;
}
.text {
  float: right;
  max-width: 450px;
}
h5 {
  font-weight: 700; 
  color: rgb(133, 91, 172);
}
p {
  line-height: 1.2;
  margin: 0;
}
a {
  font-weight: 700;
  color: rgb(133, 91, 172);
}
.right {
  display: inline-block;
  vertical-align: top;
}
img {
  width: 100%; 
}
/* -------------------------------- MEDIA QUERIES -------------------------------- */
@media (max-width: 576px) {
  .left {
    padding: 20px;
  }
  .text {
    width: 100%;
  }
  h5 {
    font-size: 12px;
  }
  p, a {
    font-size: 9px;
  }
  .right {
    height: 100%;
  }
  img {
    height: 175px;
  }
}
@media (min-width: 577px) and (max-width: 768px) {
  .text {
    width: 85%;
  }
  h5 {
    font-size: 16px;
  }
  p, a {
    font-size: 12px;
  }
}
@media (min-width: 769px) and (max-width: 992px) {
  .text {
    width: 80%
  }
  h5 {
    font-size: 24px;
  }
  p {
    margin-bottom: 5px;
  }
  p, a {
    font-size: 13px;
  }
}
@media (min-width: 993px) {
  .text {
    width: 80%;
  }
  h5 {
    font-size: 35px;
  }
  p {
    margin-bottom: 10px;
  }
  p, a {
    font-size: 16px;
  }
}
</style>
