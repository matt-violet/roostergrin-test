<template>
  <div class="footer">
    <div class="text-container">
      <p class="text">Follow Us:</p>
    </div>
    <div class="icon-container">
      <img class="icon" src="../../assets/instagram.svg">
      <img class="icon" src="../../assets/facebook.svg">
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
}
</script>

<style scoped>
.footer {
  background: rgb(248, 248, 248);
  padding: 20px;
}
.text-container {
  text-align: center;
  margin-bottom: 8px;
}
.text {
  font-size: 12px;
  font-weight: 700;
  margin: 0;
}
.icon-container {
  text-align: center;
}
.icon {
  width: 30px;
  margin: 0 5px;
  display: inline-block;
}
.icon:hover {
  cursor: pointer;
}
</style>