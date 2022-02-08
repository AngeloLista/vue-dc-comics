<template>
  <header class="container d-flex-j-between">
    <a href="#"><img src="../assets/img/dc-logo.png" alt="Logo DC" /></a>

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
      display: flex;
      align-items: center;
      li {
        display: inline-block;
        a {
          color: $secondary_color;
          padding: 52px 10px;
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