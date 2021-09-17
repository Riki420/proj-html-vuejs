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
              <a
                href="link.url"
                class="nav-link py-4 text-white"
                :class="{ selected: link.current }"
                >{{ link.text }}</a
              >
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
        <div class="col col-md-6 col-lg-6">
          <h1 class="handwrite-big">Damon Vaughn</h1>
          <p class="fs-2 text-white dm-serif">
            Best-selling author and the most influential public intellectual in
            the western world right now.
          </p>
          <address class="pumice">- New York Times</address>
          <div class="btn-arrow">
            <i class="bi bi-arrow-left-square-fill"></i>
          </div>
          <div class="btn-arrow">
            <i class="bi bi-arrow-right-square-fill"></i>
          </div>
        </div>
      </div>
    </div>
    <!--BUY ON-->
    <div class="container-fluid d-none d-sm-none d-md-inline d-lg-inline">
      <div class="row">
        <div class="col">
          <div id="buyOnBox">
            <div class="container">
              <div class="row p-4">
                <div class="col-6">
                  <figure>
                    <img
                      src="../assets/images/book-widget.png"
                      alt="book-widget"
                      class="img-fluid"
                    />
                  </figure>
                </div>
                <div class="col-6">
                  <div>
                    <h2 class="dm-serif">Latest Book Release</h2>
                    <address class="cornFlowerBlue">
                      D. VAUGHN AUTOBIOGRAPHY
                    </address>
                    <p>
                      Vestibulum tristique turpis in ipsum egestas lobortis.
                      Duis maximus bibendum volutpat. Lorem ipsum doloor sit
                      amet.
                    </p>
                  </div>
                </div>
                <div class="col-6">
                  <button type="button" class="btn btn-buy-on w-100">
                    <i class="fab fa-amazon"></i> Buy On Amazon
                  </button>
                </div>
                <div class="col-6">
                  <button type="button" class="btn btn-buy-on w-100">
                    <i class="fab fa-apple"></i> Buy On AppStore
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  components: {},
  data() {
    return {
      linksNav: [
        {
          text: "Home",
          current: true,
          url: "#",
        },
        {
          text: "About Me",
          current: false,
          url: "#",
        },
        {
          text: "Testimonials",
          current: false,
          url: "#",
        },
        {
          text: "My Blog",
          current: false,
          url: "#",
        },
        {
          text: "Meetups",
          current: false,
          url: "#",
        },
        {
          text: "Shop",
          current: false,
          url: "#",
        },
        {
          text: "Contact Me",
          current: false,
          url: "#",
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
  position: relative;
  .nav-link {
    &:hover {
      border-top: 4px solid $cornFlowerBlue;
      color: $cornFlowerBlue;
    }
  }
  .selected {
    border-top: 4px solid $cornFlowerBlue;
    color: $cornFlowerBlue;
  }
  #buyOnBox {
    background-color: #fff;
    min-height: 200px;
    position: absolute;
    bottom: 0;
    right: 0;
    width: 40%;
  }
}
</style>
