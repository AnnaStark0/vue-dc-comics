<template>
  <section>
    <h1>COMICS</h1>

    <div class="comics-list">
      <div class="comic" v-for="comic in 12" :key="comic">
        <h5>Comic Title {{ comic }}</h5>
      </div>
    </div>
  </section>
</template>


<script>
export default {
  name: "Comics",
};
</script>


<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";

h1,
h5 {
  color: $whiteText;
}
.comics-list {
  display: flex;
  flex-wrap: wrap;
}

.comic {
  background-color: lightskyblue;
  height: 250px;
  width: 25%;
}
</style>