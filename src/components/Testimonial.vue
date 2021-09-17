<template>
  <div class="container-fluid d-none d-md-inline pt-55 pb-55">
    <div class="row">
      <div class="col">
        <div class="container w-75 mt-4">
          <div class="row">
            <div class="col">
              <div class="container">
                <div class="row">
                  <!--TESTIMONIAL HEAD-->
                  <div
                    class="col d-flex justify-content-between align-items-center"
                  >
                    <div>
                      <h3 class="dm-serif">What The Critics Say</h3>
                      <p class="keppel">TESTIMONIALS FROM AROUND THE WORLD</p>
                    </div>
                    <button type="btn" class="btn btn-anzac">
                      Read All Testimonials
                    </button>
                  </div>
                </div>
                <div class="row">
                  <!--TESTIMONIAL IMG-->
                  <div class="d-none d-md-inline col-lg-6">
                    <div class="bg-testimonial round-right">
                      <div class="text-white" id="testimonialText">
                        <h4 class="dm-serif">Best Author Of His Generation</h4>
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
                  <div class="d-none d-md-inline col-lg-6 mt-md-2">
                    <div class="container-fluid">
                      <div class="row flex-column">
                        <!--FIRST TESTIMONIAL BOX-->
                        <div class="col">
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
                        <div class="col">
                          <div class="testimonials-box text-center">
                            <h4 class="dm-serif">A Unique View On The World</h4>
                            <p>
                              Donec solicitudin molestie malesuada. Curabitur
                              arcu erat, accumsan id imperdiet et, porttitor at
                              sem, Vestibulum ac diam sit amet quam vehicula
                              elementum sed sit amet dui. Nulla quis lorem ut
                              libero malesuada feugiat vestibulum ac diam sit
                              amet.
                            </p>
                          </div>
                          <div class="box-pointer"></div>
                          <address>
                            <figure class="d-inline me-2">
                              <img
                                src="../assets/images/globe-xsmall.png"
                                alt="guardian-logo"
                                class="img-fluid"
                              />
                            </figure>
                            <span class="osloGray">Mary Maxey</span>, The Globe
                            And Mail
                          </address>
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
  </div>
</template>

<script>
export default {
  name: "Testimonial",
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
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("../assets/images/testimonial2-2x.jpg");
  background-position: center;
  background-size: cover;
  padding: 4.9em;
}

//TESTIMONIALS BOX
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
