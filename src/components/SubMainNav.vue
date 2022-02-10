<template>
  <nav>
    <div class="container">
      <ul>
        <li>
          <a href="#">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
            <span>DIGITAL COMICS</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/img/buy-comics-merchandise.png" alt="" />
            <span>DC MERCHANDISE</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
            <span>SUBSCRIPTION</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
            <span>COMIC SHOP LOCATOR</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img
              class="svg-nav"
              src="../assets/img/buy-dc-power-visa.svg"
              alt=""
            />
            <span>DC POWER VISA</span>
          </a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "SubMainNav",
};
</script>

<style lang="scss" scoped>
@import "../assets/sass/_vars.scss";
nav {
  color: white;
  background-color: $main_color;
  padding: 30px 0;
  ul {
    display: flex;
    justify-content: space-around;
    list-style-type: none;
    li {
      display: flex;
      align-items: center;
      a {
        display: flex;
        align-items: center;
        color: white;
        img {
          height: 50px;
          margin-right: 15px;
        }
        .svg-nav {
          height: 35px;
        }
        span {
          font-size: 0.8rem;
        }
      }
    }
  }
}
</style>