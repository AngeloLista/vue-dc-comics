<template>
  <main>
    <div class="container">
      <p>Content goes here</p>
    </div>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss">
@import "../assets/sass/_vars.scss";

main {
  background-color: $secondary_color;
  height: 130px;
  p {
    color: white;
    line-height: 130px;
    font-weight: 700;
    font-size: 1.5rem;
  }
}
</style>