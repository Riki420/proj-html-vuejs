<template>
  <div class="container-fluid d-none d-md-block pb-55 pt-55" id="newsletter">
    <div class="row">
      <div class="col">
        <div class="container w-25">
          <div class="row">
            <!--SUBSCRIBE TEXT-->
            <div class="col-12">
              <div class="text-center text-white">
                <h2 class="dm-serif">Subscribe To My Newsletter</h2>
                <p class="cornFlowerBlue txt-small">
                  BE NOTIFIED ABOUT BOOK SIGNING TOUR DATES
                </p>
              </div>
            </div>
            <div class="col-8">
              <input
                type="email"
                name="userEmail"
                id="userEmail"
                class="w-100"
              />
            </div>
            <div class="col-4">
              <button type="button" class="btn btn-keppel">Subscribe</button>
            </div>
            <div class="col">
              <p class="osloGray">
                Donec fringilla nunc eu turpis dignissim, at euismod sapien
                tincidunt.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Newsletter",
};
</script>

<style lang="scss">
#newsletter {
  background-image: url("../assets/images/banner-2.jpg");
  background-position: center;
  background-size: cover;
  padding: 4em;
}
</style>
