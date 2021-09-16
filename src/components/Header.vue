<template>
  <!--Header-->
  <header>
    <div class="container pb-4">
      <!--LOGO & NAVBAR-->
      <div class="row">
        <!--LOGO-->
        <div class="col">
          <figure>
            <img
              src="../assets/images/author-logo-round-200x205.png"
              alt="logo"
              class="img-fluid"
            />
          </figure>
        </div>
        <!--NAVBAR-->
        <div class="col-7">
          <ul class="nav">
            <li class="nav-item" v-for="(link, index) in linksNav" :key="index">
              <a href="#" class="nav-link py-4 text-white">{{ link.text }}</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link text-white py-4"
                ><i class="bi bi-cart-fill"></i
              ></a>
            </li>
          </ul>
        </div>
      </div>
      <!--AUTHOR & CIT-->
      <div class="row ps-4">
        <div class="col-6">
          <h1 class="handwrite-big">Damon Vaughn</h1>
          <p class="fs-2 text-white dm-serif">
            Best-selling author and the most influential public intellectual in
            the western world right now.
          </p>
          <address class="pumice">- New York Times</address>
          <div class="btn-arrow"><i class="bi bi-arrow-left-square-fill"></i></div>
          <div class="btn-arrow"><i class="bi bi-arrow-right-square-fill"></i></div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      linksNav: [
        {
          text: "Home",
        },
        {
          text: "About Me",
        },
        {
          text: "Testimonials",
        },
        {
          text: "My Blog",
        },
        {
          text: "Meetups",
        },
        {
          text: "Shop",
        },
        {
          text: "Contact Me",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/_vars.scss";
@import "../assets/scss/_text.scss";
header {
  background-image: url("../assets/images/hero-07-2x.jpg");
  background-size: cover;
  background-position: top;
  background-repeat: no-repeat;
  min-height: 500px;
  .nav-link {
    &:hover {
      border-top: 4px solid $cornFlowerBlue;
      color: $cornFlowerBlue;
    }
  }
}
</style>
