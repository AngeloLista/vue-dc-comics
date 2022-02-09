<template>
  <main>
    <Jumbotron />
    <div class="container" id="products">
      <ProductCard />
    </div>
  </main>
</template>

<script>
import Jumbotron from "./Jumbotron.vue";
import ProductCard from "./ProductCard.vue";

export default {
  name: "Main",
  components: {
    Jumbotron,
    ProductCard,
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";

main {
  background-color: $secondary_color;
  p {
    color: white;
    line-height: 130px;
    font-size: 1.5rem;
  }
  #products {
    padding: 50px 0;
    display: flex;
    flex-wrap: wrap;
  }
}
</style>