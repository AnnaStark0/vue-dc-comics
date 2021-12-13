<template>
  <div id="app">
    <Header />
    <MainUno />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import MainUno from './components/MainUno.vue';
import Footer from './components/Footer.vue';

export default {
  name: "App",
  components: {
    Header,
    MainUno,
    Footer
  },
};
</script>

<style lang="scss">
@import './assets/style/global.scss';

</style>
