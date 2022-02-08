<template>
  <section id="footer-top">
    <div class="d-flex justyify-space-between container">
      <nav>
        <section>
          <h3>DC COMICS</h3>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </section>
        <section>
          <h3>DC</h3>
          <ul>
            <li><a href="#">Terms of Use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </section>
        <section>
          <h3>SITES</h3>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </section>
      </nav>
      <div class="dc-logo-bg"></div>
    </div>
  </section>
</template>

<script>
export default {
  name: "FooterTop",
};
</script>

<style lang="scss" scoped>
@import "../../assets/sass/_utils.scss";

#footer-top {
  background-image: url("../../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  nav {
    display: flex;
    margin: 30px 0;
    section {
      width: calc(100% / 3);
      padding-right: 50px;
      display: inline-block;
      h3 {
        margin: 15px 0;
      }
      ul {
        display: inline-block;
        list-style-type: none;
        li {
          padding: 3px 0;
          a {
            font-size: 0.8rem;
            color: #bbbbbb;
            &:hover {
              text-decoration: underline;
            }
          }
        }
      }
    }
  }
  .dc-logo-bg {
    width: 500px;
    background-image: url("../../assets/img/dc-logo-bg.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position-y: center;
  }
}
</style>