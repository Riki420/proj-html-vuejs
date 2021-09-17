<template>
  <div
    class="container-fluid bg-foot d-flex align-items-center align-content-center"
  >
    <div class="row p-4 justify-content-center flex-grow-1 align-items-center">
      <!--LOGO FOOTER-->
      <div class="col">
        <figure>
          <img
            src="../assets/images/author-logo-round-small.png"
            alt="logo-foot"
            class="img-fluid"
          />
        </figure>
      </div>
      <!--ABOUT ME-->
      <div class="col d-none d-md-block d-flex flex-column">
        <div>
          <h4 class="dm-serif text-white pb-2">ABOUT ME</h4>
        </div>
        <div>
          <p class="text-white">
            Vivamus suscipit tortor eget felis porttitor volupat. Nulla quis
            lorem ut libero malesuada feugiat. Vivamus suscipit tortor eget
            felis porttitor volupat.
          </p>
        </div>
      </div>
      <!--USEFUL LINKS-->
      <div class="col d-none d-md-block d-flex flex-column">
        <div>
          <h4 class="dm-serif text-white pb-2 indent-2">USEFUL LINKS</h4>
        </div>
        <div>
          <ul class="text-white list-style-none">
            <li>
              <a href="#"
                ><i class="fas fa-chevron-right me-2"></i>Latest Books</a
              >
            </li>
            <li>
              <a href="#"
                ><i class="fas fa-chevron-right me-2"></i>Upcoming Events</a
              >
            </li>
            <li>
              <a href="#"
                ><i class="fas fa-chevron-right me-2"></i>Recent Articles</a
              >
            </li>
            <li>
              <a href="#"
                ><i class="fas fa-chevron-right me-2"></i>Buisness Enquiries</a
              >
            </li>
            <li>
              <i class="fas fa-chevron-right me-2"></i>Visit My Foundation
            </li>
          </ul>
        </div>
      </div>
      <!--CONTACT INFO-->
      <div class="col d-flex flex-column">
        <div>
          <h4 class="dm-serif text-white pb-2 indent-2">CONTACT INFO</h4>
        </div>
        <div>
          <ul class="text-white list-style-none">
            <li>63 E. Studebaker Street Bollingbrook, IL 60440</li>
            <li>Phone: (800)000-0000</li>
            <li>Mobile: (800)000-0000</li>
            <li>Email: info@your-company-com</li>
          </ul>
          <ul class="d-flex list-style-none text-white">
            <li>
              <a href="#"><i class="fab fa-facebook me-2"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-twitter me-2"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-instagram me-2"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-linkedin me-2"></i></a>
            </li>
            <li>
              <a href="#"><i class="fab fa-youtube me-2"></i></a>
            </li>
          </ul>
        </div>
      </div>
      <!--COPYRIGHT-->
      <div class="col-12 text-center text-white mt-4">
        &copy; Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Rights
        Reserved | Powered by WordPress
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss">
.bg-foot {
  background-image: url("../assets/images/footer-3.jpg");
  background-position: top;
  background-size: cover;
  min-height: 400px;
}
.list-inline {
  display: block;
}
.list-style-none {
  list-style: none;
  a {
    text-decoration: none;
    color: #fff;
  }
}
</style>
