<template>
  <div class="card">
    <img class="card-thumbnail" :src="product.thumb" alt="" />
    <span>{{ product.series }}</span>
  </div>
</template>

<script>
export default {
  name: "ProductCard",
  props: ["product"],
};
</script>

<style lang="scss" scoped>
.card {
  color: white;
  display: inline-block;
  width: calc(100% / 6);
  margin: 30px 0;
  .card-thumbnail {
    height: 170px;
    width: 170px;
    margin-bottom: 15px;

    object-fit: cover;
    object-position: top;
  }
  span {
    font-weight: 600;
    text-transform: uppercase;
  }
}
</style>