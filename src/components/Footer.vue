<template>
  <footer>
    <FooterTop />
    <FooterBottom />
  </footer>
</template>

<script>
import FooterTop from "./footer/FooterTop.vue";
import FooterBottom from "./footer/FooterBottom.vue";

export default {
  name: "Footer",
  components: {
    FooterTop,
    FooterBottom,
  },
};
</script>

<style>
</style>