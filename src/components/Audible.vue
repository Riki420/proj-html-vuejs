<template>
  <div id="audible" class="container-fluid pt-4 position-relative">
    <div class="row">
      <div class="col">
        <div class="container w-75">
          <div class="row">
            <div class="col-6">
              <!--MOBILE AUDIBLE PIC-->
              <figure class="d-flex justify-content-end">
                <img
                  src="../assets/images/audible-app-2x.png"
                  alt="audible-app"
                  class="img-fluid w-50"
                />
              </figure>
            </div>
            <!--NEW AUDIBLE-->
            <div class="col-6 d-flex align-items-center">
              <div class="text-center">
                <h4 class="text-white">New Audiobook</h4>
                <h6 class="saffron">
                  NO TIME TO READ? NO PROBLEM. LISTEN TO IT
                </h6>
                <p class="text-white">
                  Donec fringilla nunc eu turpis dignissim, at euismod sapien
                  tincidunt. Maecenas eleifend congue cursus.
                </p>
                <div class="d-flex justify-content-between">
                  <figure>
                    <img
                      src="../assets/images/audible-logo.png"
                      alt="audible-logo"
                      class="img-fluid"
                    />
                  </figure>
                  <figure>
                    <img
                      src="../assets/images/bn-logo-tall.png"
                      alt="audible-logo"
                      class="img-fluid"
                    />
                  </figure>
                  <figure>
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
</style>
