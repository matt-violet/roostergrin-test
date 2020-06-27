<template>
  <div class="row-one container col-12 no-gutters">
    <div class="col-6 left">
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
  }
  .text {
    padding: 60px 40px;
    width: 300px;
    float: right;
  }
  h5 {
    font-weight: 700; 
    color: rgb(133, 91, 172);
  }
  p {
    font-size: 10px;
    line-height: 1.2;
    margin: 0;
  }
  a {
    font-size: 10px;
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
</style>
