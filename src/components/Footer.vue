<template>
  <footer>
    <!--FOOTER UP-->
    <div class="footerUp">
      <div class="container"></div>
    </div>
    <!--///FOOTER UP-->

    <!--FOOTER DOWN-->
    <div class="footerDOwn">
      <div class="container"></div>
    </div>
    <!--///FOOTER DOWN-->
  </footer>
</template>



<script>
export default {
  name: "Footer",
};
</script>


<style lang='scss' scoped>
footer {
  height: 500px;
  background-color: grey;

  .footerUp {
    height: 70%;
    background-image: url("../assets/img/footer-bg.jpg");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
  }
}
</style>