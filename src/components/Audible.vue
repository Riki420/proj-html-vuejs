<template>
  <div id="audible" class="container-fluid pt-4 position-relative">
    <div class="row">
      <div class="col">
        <div class="container w-75">
          <div class="row justify-content-center">
            <div
              class="col-md-6 col-lg-6 d-flex d-none d-sm-none d-md-inline d-lg-inline"
            >
              <!--MOBILE AUDIBLE PIC-->
              <figure id="audiblePic" class="d-flex justify-content-end">
                <img
                  src="../assets/images/audible-app-2x.png"
                  alt="audible-app"
                  class="img-fluid"
                />
              </figure>
            </div>
            <!--NEW AUDIBLE-->
            <div class="col col-md-6 col-lg-6 d-flex align-items-center">
              <div class="text-center">
                <h2 class="text-white dm-serif">New Audiobook</h2>
                <h6 class="cornFlowerBlue">
                  NO TIME TO READ? NO PROBLEM. LISTEN TO IT
                </h6>
                <p class="text-white">
                  Donec fringilla nunc eu turpis dignissim, at euismod sapien
                  tincidunt. Maecenas eleifend congue cursus.
                </p>
                <div class="d-flex justify-content-center">
                  <figure class="me-2">
                    <img
                      src="../assets/images/audible-logo.png"
                      alt="audible-logo"
                      class="img-fluid"
                    />
                  </figure>
                  <figure class="me-3">
                    <img
                      src="../assets/images/bn-logo-tall.png"
                      alt="audible-logo"
                      class="img-fluid"
                    />
                  </figure>
                  <figure class="me-2">
                    <img
                      src="../assets/images/kindle-logo-tall.png"
                      alt="audible-logo"
                      class="img-fluid"
                    />
                  </figure>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Audible",
};
</script>

<style lang="scss">
#audible {
  background-image: url("../assets/images/banner.jpg");
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
#audiblePic {
  margin: 0;
}
</style>
