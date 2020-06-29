<template>
  <div class="container-fluid col-12">
    <div class="row align-items-center no-gutters">
      <div class="left col-12 col-sm-6 no-gutters">
        <div class="left-text col-12 col-sm-10 offset-sm-4 offset-md-5 col-xl-7">
          <h5>LOREM IPSUM</h5>
          <h5>DOLOR SIT AMET</h5>
          <p class="stars">&#9733; &#9733; &#9733; &#9733; &#9733;</p>
        </div>
      </div>
      <div class="right col-12 col-sm-6 col-md-4 offset-md-1 col-lg-4">
        <div id="carousel" class="carousel slide" data-ride="carousel">
          <!-- indicators -->
          <ol class="carousel-indicators">
            <li data-target="#carousel" data-slide-to="0" class="active-indicator">.</li>
            <li data-target="#carousel" data-slide-to="1">.</li>
            <li data-target="#carousel" data-slide-to="2">.</li>
          </ol>
          <!-- slides -->
          <div class="carousel-inner" role="listbox">
            <div class="carousel-item active">
              <p class="carousel-header">John Doe 08/08/2019</p>
              <p class="carousel-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates, inventore saepe et delectus facere voluptas! Incidunt explicabo nesciunt illo possimus, inventore dolore facere ratione officiis hic perferendis nam tempora eos. Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam vero architecto corrupti ea maxime tempora error! Officia fuga iste esse maiores in eius, vero ratione quos sint! Exercitationem, atque totam.</p>
            </div>
            <div class="carousel-item">
              <p class="carousel-header">John Doe 08/08/2019</p>
              <p class="carousel-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nesciunt quaerat, delectus necessitatibus nulla, dignissimos ducimus aperiam qui quae ut dolores quisquam dolorum architecto pariatur omnis nam soluta, deserunt dolore suscipit. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Itaque vitae quis provident, veniam blanditiis iusto non quod maxime praesentium explicabo id consequatur inventore quaerat quibusdam cumque reiciendis, incidunt suscipit rem.</p>
            </div>
            <div class="carousel-item">
              <p class="carousel-header">John Doe 08/08/2019</p>
              <p class="carousel-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita corporis molestias, sequi fugit nisi, eaque, voluptate temporibus incidunt quaerat culpa et? Repellat sequi error esse qui hic similique excepturi voluptate? Lorem ipsum, dolor sit amet consectetur adipisicing elit. Obcaecati aperiam molestias repudiandae ducimus nam vero ea suscipit neque ipsa eius, placeat quasi inventore quos dolores nemo corrupti ex perspiciatis. Eaque?</p>
            </div>
          </div>
          <!-- controls -->
          <a class="carousel-control-prev" href="#carousel" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon arrow">&lsaquo;</span>
          </a>
          <a class="carousel-control-next" href="#carousel" role="button" data-slide="next">
            <span class="carousel-control-next-icon arrow">&rsaquo;</span>
          </a>
        </div>
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
  padding: 50px 20px 0 20px;
}
.left-text {
  text-align: center;
  max-width: 350px;
}
h5 {
  font-weight: 700;
  font-size: 22px;
  margin: 3px 0;
}
.stars {
  display: block;
  font-weight: 700;
  color: rgb(255, 119, 41);
}
.right {
  display: inline-block;
  vertical-align: top;
  padding: 20px 50px;
}
img {
  width: 100%; 
}
.carousel {
  max-width: 500px;
}
.carousel-inner {
  padding: 0 30px 20px 30px;
}
.arrow {
  font-size: 40px;
  font-weight: 200;
  color: black;
  display: flex;
  justify-content: center;
  align-items: center;
}
.carousel-control-prev {
  transition: .5s;
  margin-left: -30px;
}
.carousel-control-next {
  transition: .5s;
  margin-right: -30px;
}
.carousel-indicators {
  margin: 30px 0 0 0;
}
.carousel-control-next:hover, .carousel-control-prev:hover, .arrow {
  transform: scale(1.3);
}
li {
  width: 5px;
  height: 5px;
  margin: -5px 2px;
  background-color: gold;
  border-radius: 50%;
}
.active-indicator {
  background-color: goldenrod;
}
.carousel-header {
  color: rgb(133, 91, 172);
  text-align: center;
  font-weight: 700;
  font-size: 12px;
  margin: 0 auto 10px auto;
}
.carousel-text {
  font-size: 12px;
  line-height: 1.2;
  margin: 0;
}
/* -------------------------------- MEDIA QUERIES -------------------------------- */
@media (max-width: 575px) {
  .left-text {
    margin: auto;
  }
}
@media (min-width: 576px) {
  h5 {
    font-size: 22px;
  }
  .stars {
    font-size: 16px;
  }
  .left-text {
    text-align: left;
  }
  .right {
    padding: 50px;
  }
  .carousel-inner {
    padding: 0 10px 20px 10px;
  }
  .carousel-text, .carousel-header {
    font-size: 12px;
  }
  .carousel-control-next {
    margin-right: -20px;
  }
}
@media (min-width: 768px) {
  h5 {
    font-size: 28px;
  }
  .stars {
    font-size: 20px;
  }
  .carousel-text, .carousel-header {
    font-size: 14px;
  }
  .right {
    padding: 75px 0;
  }
  .carousel-control-prev {
    margin-left: -40px;
  }
  .carousel-control-next {
    margin-right: -40px;
  }
}
@media (min-width: 992px) {
  h5 {
    font-size: 35px;
  }
  .stars {
    font-size: 24px;
  }
  .right {
    padding: 100px 0;
  }
  .carousel-inner {
    padding: 0 30px 20px 30px;
  }
  .carousel-text, .carousel-header {
    font-size: 16px;
  }
}
</style>
