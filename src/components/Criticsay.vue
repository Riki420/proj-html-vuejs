<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col">
        <div class="container w-75 mt-4">
          <div class="row">
            <div class="col">
              <div class="container">
                <div class="row">
                  <!--Head Section-->
                  <div
                    class="col d-flex justify-content-between align-items-center"
                  >
                    <div>
                      <h1 class="dm-serif">What The Critics Say</h1>
                      <p class="keppel">TESTIMONIALS FROM AROUND THE WORLD</p>
                    </div>
                    <button type="btn" class="btn btn-anzac">
                      Read All Testimonials
                    </button>
                  </div>
                </div>
                <div class="row">
                  <!--TESTIMONIAL IMG-->
                  <div class="col-6">
                    <div class="bg-testimonial round-right filter-bright">
                      <div class="text-white">
                        <h1 class="dm-serif">Best Author Of His Generation</h1>
                        <hr />
                        <h5>This book will change your perspective on life</h5>
                        <p>
                          Donec fringilla nunc eu turpis dignissim, at euismod
                          sapien tincidunt. Maecenas eleifend congue cursus. In
                          vitae enim quis sem pharetra. Curabitur arcu erat,
                          accumsan id imperdiet et, porttitor at sem.
                        </p>
                        <p>
                          Donec fringilla nunc eu turpis dignissim, at euismod
                          sapien tincidunt. Maecenas eleifend congue cursus. In
                          vitae enim quis sem pharetra. Curabitur arcu erat,
                          accumsan id imperdiet et, porttitor at sem.
                        </p>
                        <address>
                          <figure class="d-inline">
                            <img
                              src="../assets/images/nytimes-logo-white-xsmall.png"
                              alt="NYT-logo"
                              class="img-fluid me-2"
                            />
                          </figure>
                          Justine Kilpatrick,
                          <span class="keppel">The New York Times</span>
                        </address>
                      </div>
                    </div>
                  </div>
                  <!--TESTIMONIALS TEXT-->
                  <div class="col-6">
                    <div class="container-fluid">
                      <div class="row flex-column">
                        <div class="col">
                          <!--FIRST TESTIMONIAL BOX-->
                          <div class="testimonials-box text-center">
                            <h4 class="dm-serif">A True Masterpiece, Bravo!</h4>
                            <p>
                              Nulla quis lorem ut libero malesuada feugiat.
                              Vivamus magna justo, lacinia eget consectetur sed,
                              convallis at tellus. Vivamus scipit tortor eget
                              felis porttitor volupat. Nulla quis lorem ut
                              libero malesuada feug at.
                            </p>
                          </div>
                          <div class="box-pointer"></div>
                          <address>
                            <figure class="d-inline me-2">
                              <img
                                src="../assets/images/theguardian-xsmall.png"
                                alt="guardian-logo"
                                class="img-fluid"
                              />
                            </figure>
                            <span class="osloGray">Gerald Hendley</span>, The
                            Guardian
                          </address>
                        </div>
                        <!--SECOND TESTIMONIAL BOX-->
                        <div class="col"></div>
                      </div>
                    </div>
                  </div>
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
  name: "Criticsay",
};
</script>

<style lang="scss">
@import "../assets/scss/_vars.scss";

//Filter Class
.round-right {
  border-radius: 0 0 40px 0;
}
.filter-bright {
  filter: brightness(0.5);
}

//Testimonials class
.bg-testimonial {
  background-image: url("../assets/images/testimonial2-2x.jpg");
  background-position: center;
  background-size: cover;
  background-image: linear-gradient(0, 0, 0, 0.5);
  padding: 2em;
}
.testimonials-box {
  min-height: 200px;
  background-color: $dawnPink;
  padding: 40px;
}
.box-pointer {
  height: 30px;
  width: 30px;
  background: $dawnPink;
  margin: 0 auto;
  transform: rotate(45deg);
  border-radius: 0 0 3px 0;
  margin-top: -22px;
  position: relative;
  left: calc(0.2vw - 100px);
}
</style>
