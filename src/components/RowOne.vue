<template>
  <div class="container-fluid col-12">
    <div class="row align-items-center no-gutters">
      <div class="left col-12 col-sm-6 no-gutters">
        <div class="col-9 offset-2 col-md-6 offset-md-4">
          <h5>LOREM IPSUM</h5>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nulla alias iste assumenda labore repellendus a vitae unde ullam consectetur, nemo repudiandae rerum deleniti facilis, explicabo eos dicta quaerat voluptatum temporibus!</p>
          <a @click="$emit('visitLink', false)">> Lorem Ipsum</a>
        </div>
      </div>
      <div class="col-6 right">
        <img src="../../assets/img-1.jpg">
      </div>
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
  padding: 50px 0;
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
a:hover {
  cursor: pointer;
}
.right {
  display: inline-block;
  vertical-align: top;
}
img {
  width: 100%;
  min-height: 260px;
}
/* -------------------------------- MEDIA QUERIES -------------------------------- */
@media (max-width: 576px) {
  h5 {
    font-size: 22px;
  }
  p, a {
    font-size: 12px;
  }
  .right {
    height: 0;
    width: 0;
    visibility: hidden;
  }
}
@media (min-width: 577px) and (max-width: 768px) {
  h5 {
    font-size: 16px;
  }
  p, a {
    font-size: 12px;
  }
}
@media (min-width: 769px) and (max-width: 992px) {
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
