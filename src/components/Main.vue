<template>
  <main>
    <Jumbotron />
    <div class="container">
      <p>Content goes here</p>
    </div>
  </main>
</template>

<script>
import Jumbotron from "./Jumbotron.vue";
export default {
  name: "Main",
  components: {
    Jumbotron,
  },
};
</script>

<style lang="scss">
@import "../assets/sass/_vars.scss";

main {
  background-color: $secondary_color;

  p {
    color: white;
    line-height: 130px;
    font-weight: 700;
    font-size: 1.5rem;
  }
}
</style>