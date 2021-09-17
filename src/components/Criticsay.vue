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
.round-right {
  border-radius: 0 0 40px 0;
}
.filter-bright {
  filter: brightness(0.5);
  p {
    filter: brightness(1);
  }
}
.bg-testimonial {
  background-image: url("../assets/images/testimonial2-2x.jpg");
  background-position: center;
  background-size: cover;
  padding: 2em;
}
</style>
