<template>
  <main>
    <Jumbotron />
    <div class="title container">
      <h2>CURRENT SERIES</h2>
    </div>
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
  .title {
    color: white;
    margin-top: -1.6rem;
    h2 {
      background-color: $main_color;
      display: inline-block;
      padding: 10px 30px;
    }
  }
  p {
    color: white;
    line-height: 130px;
    font-size: 1.5rem;
  }
  #products {
    padding: 25px 0;
    display: flex;
    flex-wrap: wrap;
  }
}
</style>