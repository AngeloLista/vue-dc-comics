<template>
  <div id="app">
    <Header />
    <Main />
    <SubMainNav />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
import SubMainNav from "./components/SubMainNav.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    SubMainNav,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
