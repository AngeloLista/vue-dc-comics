<template>
  <section id="footer-top">
    <div class="d-flex justyify-space-between container">
      <nav>
        <section v-for="(nav_section, index) in nav_sections" :key="index">
          <!-- Titolo -->
          <h3>{{ nav_section.title }}</h3>
          <!-- Links -->
          <ul>
            <li v-for="(text, index) in nav_section.texts" :key="index">
              <a href="#">{{ text }}</a>
            </li>
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
  data() {
    return {
      nav_sections: [
        {
          title: "DC COMICS",
          texts: [
            "Characters",
            "Comics",
            "Movies",
            "TV",
            "Games",
            "Videos",
            "News",
          ],
        },
        { title: "SHOP", texts: ["Shop DC", "Shop DC Collectibles"] },
        {
          title: "DC",
          texts: [
            "Terms of Use",
            "Privacy policy (New)",
            "Ad Choices",
            "Advertising",
            "Jobs",
            "Subscriptions",
            "Talent Workshops",
            "CPSC Certificates",
            "Ratings",
            "Shop Help",
            "Contact Us",
          ],
        },
        {
          title: "SITES",
          texts: [
            "DC",
            "MAD Magazine",
            "DC Kids",
            "DC Universe",
            "DC Power Visa",
          ],
        },
      ],
    };
  },
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