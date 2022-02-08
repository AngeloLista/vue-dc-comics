<template>
  <footer>
    <div class="container">
      <FooterTop />
      <FooterBottom />
    </div>
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
footer {
  background-image: url("../assets/img/footer-bg.jpg");
  color: white;
  padding: 30px 0;
}
</style>