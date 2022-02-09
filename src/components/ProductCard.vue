<template>
  <div class="card">
    <div class="card-thumbnail"></div>
    <span>ACTION COMICS</span>
  </div>
</template>

<script>
export default {
  name: "ProductCard",
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

    background-image: url("https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX");
    background-size: cover;
    background-repeat: no-repeat;
    background-position-x: center;
  }
  span {
    font-weight: 600;
  }
}
</style>