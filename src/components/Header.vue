<template>
  <header>
    <div class="container">
      <!--Logo-->
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="Logo Dc" />
      </div>
      <!--///Logo-->

      <!--Nav-->
      <nav>
        <ul>
          <li><a href="#"> characters </a></li>
          <li><a href="#"> comics </a></li>
          <li><a href="#"> movies </a></li>
          <li><a href="#"> tv </a></li>
          <li><a href="#"> games</a></li>
          <li><a href="#"> collectibles</a></li>
          <li><a href="#"> videos</a></li>
          <li><a href="#"> fans</a></li>
          <li><a href="#"> news</a></li>
          <li><a href="#"> shop</a></li>
        </ul>
      </nav>
      <!--///Nav-->
    </div>
  </header>
</template>



<script>
export default {
  name: "Header",
};
</script>



<style lang='scss' scoped>
@import "../assets/style/partials/variables.scss";

header {
    height: 100px;
    margin: 20px 0 20px 0;

  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;

    

    nav {
     
    font-family: Arial, Helvetica, sans-serif;

      ul {
        list-style: none;

        display: flex;
        justify-content: center;

        li a {
          display: inline-block;
          padding: 20px;
          text-decoration: none;
          text-transform: uppercase;
          color: black;

        }
      }
    }
  }
}
</style>
