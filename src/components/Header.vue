<template>
  <header class="container d-flex-j-between">
    <a href="#"><img src="../assets/img/dc-logo.png" alt="Logo DC" /></a>

    <nav>
      <ul>
        <li v-for="(link, index) in links" :key="index">
          <a :class="{ active: link.active }" href="#">{{ link.text }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        { text: "CHARACTERS", url: "#", active: true },
        { text: "COMICS", url: "#", active: false },
        { text: "MOVIES", url: "#", active: false },
        { text: "TV", url: "#", active: false },
        { text: "GAMES", url: "#", active: false },
        { text: "COLLECTIBLES", url: "#", active: false },
        { text: "VIDEOS", url: "#", active: false },
        { text: "FANS", url: "#", active: false },
        { text: "NEWS", url: "#", active: false },
        { text: "SHOP", url: "#", active: false },
      ],
    };
  },
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
          &.active {
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