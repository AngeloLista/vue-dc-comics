<template>
  <div class="card">
    <a href="#">
      <img class="card-thumbnail" :src="product.thumb" alt="" />
      <span>{{ product.series }}</span>
    </a>
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
  display: inline-block;
  width: calc(100% / 6);
  margin: 30px 0;
  a {
    color: white;

    .card-thumbnail {
      height: 170px;
      width: 170px;
      margin-bottom: 15px;

      object-fit: cover;
      object-position: top;
    }
    span {
      font-weight: 600;
      font-size: 0.9rem;
      text-transform: uppercase;
    }
  }
}
</style>