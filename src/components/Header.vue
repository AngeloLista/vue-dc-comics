<template>
  <header class="container d-flex-j-between">
    <img src="../assets/img/dc-logo.png" alt="Logo DC" />

    <nav>
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";

header {
  font-size: 0.8rem;
  font-weight: 700;
  height: 130px;
  img {
    width: 85px;
  }
  nav {
    height: 100%;
    ul {
      height: 100%;
      display: inline-block;
      li {
        display: inline-block;
        line-height: 130px;
        a {
          line-height: 55px;
          color: $secondary_color;
          padding: 0 10px;
          &:hover {
            color: $main_color;
            border-bottom: 5px solid $main_color;
          }
        }
      }
    }
  }
}

.d-flex-j-between {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>s