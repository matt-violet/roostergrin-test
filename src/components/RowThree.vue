<template>
  <div class="container-fluid col-12">
    <div class="row no-gutters">
      <div class="left col-xs-6 col-sm-6 no-gutters">
        <div class="text col-8 offset-1 col-sm-7 offset-sm-3 col-lg-6 offset-lg-4">
          <h5>LOREM IPSUM</h5>
          <h5>DOLOR SIT AMET</h5>
          <p class="paragraph">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nulla alias iste assumenda labore repellendus a vitae unde ullam consectetur, nemo repudiandae rerum deleniti facilis, explicabo eos dicta quaerat voluptatum temporibus!</p>
          <a class="link" href="">> Lorem Ipsum</a>
        </div>
      </div>
      <div class="right col-12 col-sm-6 no-gutters">
        <div class="col-12 col-lg-10 offset-lg-0">
          <div class="top-icons">
            <div class="icon-container">
              <img class="icon" src="../../assets/home-expertise.svg">
              <p class="icon-text">LOREM</p>
            </div>
            <div class="icon-container">
              <img class="icon" src="../../assets/home-hygiene.svg">
              <p class="icon-text">LOREM ISPUM</p>
            </div>
          </div>
          <div class="bottom-icons">
            <div class="icon-container">
              <img class="icon" src="../../assets/home-lab.svg">
              <p class="icon-text">LOREM IPSUM</p>
            </div>
            <div class="icon-container">
              <img class="icon" src="../../assets/home-retention.svg">
              <p class="icon-text">LOREM</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RowThree",
}
</script>

<style scoped>
.left, .right {
  padding: 50px 0;
}
.left {
  vertical-align: top;
  display: flex;
  justify-content: center;
  align-items: center; 
}
.right {
  background: rgb(248, 248, 248);
}
h5 {
  font-weight: 700;
  font-size: 22px;
  margin: 0;
}
.paragraph {
  font-size: 12px;
  line-height: 1.2;
  margin: 5px 0 5px 0;
}
.link {
  font-size: 12px;
  font-weight: 700;
  color: rgb(133, 91, 172);
}
.bottom-icons, .top-icons {
  margin: 10px 0;
  text-align: center;
}
.icon-container {
  display: inline-block;
  margin: 5px 10px;
  text-align: center;
  width: 75px;
}
.icon {
  width: 60px;
  height: 60px;
  padding: 0 10px;
  border: .5px solid rgb(133, 91, 172);
  border-radius: 50%;
}
.icon-text {
  font-weight: 700;
  font-size: 10px;
  margin: 10px 0 0 0;
}
/* -------------------------------- MEDIA QUERIES -------------------------------- */
@media (max-width: 576px) {
  .left {
    padding: 0;
  }
  .right {
    padding: 40px;
    text-align: center;
  }
  .text {
    padding: 50px 0;
  }
  h5 {
    font-size: 22px;
    font-weight: 900;
  }
  .paragraph {
    font-size: 12px;
  }
  .top-icons, .bottom-icons {
    margin: 0;
  }
  .icon-container {
    margin: 15px;
  }
}
@media (min-width: 769px) and (max-width: 992px) {
  h5 {
    font-size: 26px;
  }
  .paragraph, .link {
    font-size: 12px;
  }
  .icon-container {
    margin: 10px 25px;
    width: 100px;
  }
  .icon {
    width: 70px;
    height: 70px;
    padding: 0 10px;
  }
  .icon-text {
    font-size: 14px;
  }
}
@media (min-width: 993px) {
  h5 {
    font-size: 28px;
  }
  .paragraph, .link {
    font-size: 16px;
  }
  .paragraph {
    margin-bottom: 15px;
    line-height: 1.2;
  }
  .icon-container {
    margin: 10px 40px;
    width: 100px;
  }
  .icon {
    padding: 0 14px;
    width: 80px;
    height: 80px;
  }
  .icon-text {
    font-size: 14px;
  }
}
</style>
