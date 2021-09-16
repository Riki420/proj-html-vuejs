<template>
  <div class="container-fluid p-4 bgDawnPink">
    <div class="row">
      <div class="col align-items-center">
        <div class="container w-75">
          <div class="row justify-content-center align-items-center">
            <div class="col-6 col-md">
              <figure>
                <img
                  src="../assets/images/ebay-logotan-2x.png"
                  alt="ebay-logo"
                  class="img-fluid"
                />
              </figure>
            </div>
            <div class="col-6 col-md">
              <figure>
                <img
                  src="../assets/images/audible-logotan-2x.png"
                  alt="ebay-logo"
                  class="img-fluid"
                />
              </figure>
            </div>
            <div class="col-6 col-md">
              <figure>
                <img
                  src="../assets/images/bb-logotan-2x.png"
                  alt="ebay-logo"
                  class="img-fluid"
                />
              </figure>
            </div>
            <div class="col-6 col-md">
              <figure>
                <img
                  src="../assets/images/kindlefire-logotan-2x.png"
                  alt="ebay-logo"
                  class="img-fluid"
                />
              </figure>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Logotan",
};
</script>

<style lang="scss">
@import "../assets/scss/_vars.scss";
.bgDawnPink {
  background-color: $dawnPink;
}
</style>
