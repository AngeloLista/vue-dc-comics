<template>
  <div id="footer-bottom">
    <div class="container d-flex align-items-center justyify-space-between">
      <div id="sign-up"><a href="#">SIGN-UP NOW!</a></div>
      <div id="socials">
        <h3>FOLLOW US</h3>
        <ul>
          <li>
            <a href="#"
              ><img
                src="../../assets/img/footer-facebook.png"
                alt="Facebook Logo"
            /></a>
          </li>
          <li>
            <a href="#"
              ><img src="../../assets/img/footer-twitter.png" alt=""
            /></a>
          </li>
          <li>
            <a href="#"
              ><img src="../../assets/img/footer-youtube.png" alt=""
            /></a>
          </li>
          <li>
            <a href="#"
              ><img src="../../assets/img/footer-pinterest.png" alt=""
            /></a>
          </li>
          <li>
            <a href="#"
              ><img src="../../assets/img/footer-periscope.png" alt=""
            /></a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterBottom",
};
</script>

<style lang="scss" scoped>
@import "../../assets/sass/_utils.scss";
@import "../../assets/sass/_vars.scss";

#footer-bottom {
  background-color: #303030;
  #sign-up {
    padding: 50px 0;
    a {
      color: white;
      padding: 15px;
      border: 3px solid $main_color;
      &:hover {
        background-color: $main_color;
      }
    }
  }
  #socials {
    display: flex;
    align-items: center;
    h3 {
      color: $main_color;
      display: inline-block;
      margin-right: 15px;
    }
    ul {
      list-style-type: none;
      display: inline-block;
      li {
        display: inline-block;
        margin: 0 6px;
        &:hover {
          transform: scale(1.1);
        }
      }
    }
  }
}
</style>