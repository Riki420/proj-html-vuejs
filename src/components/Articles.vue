<template>
  <div class="container-fluid d-none d-md-block bgDawnPink pb-55 pt-55">
    <div class="row">
      <div class="col">
        <div class="container w-75 mt-4">
          <div class="row">
            <div class="col">
              <div class="container">
                <div class="row">
                  <!--ARTICLE HEAD-->
                  <div
                    class="col-12 d-flex justify-content-between align-items-center"
                  >
                    <div>
                      <h3 class="dm-serif">Recent Articles</h3>
                      <p class="keppel">READ THE LATEST ENTRIES</p>
                    </div>
                    <button type="btn" class="btn btn-anzac">
                      All Articles
                    </button>
                  </div>
                  <!--LARGE ARTICLE-->
                  <div class="col-8">
                    <div class="card p-4">
                      <div class="card-body">
                        <figure>
                          <img
                            src="../assets/images/20-Tips-scaled.jpg"
                            alt=""
                            class="img-fluid"
                          />
                        </figure>
                        <h4>20 Creativity Tips</h4>
                        <address class="txt-small">
                          By admin | October 24th, 2019 | Categories: Event,
                          Tips & Tricks
                        </address>
                        <p>
                          Vestibulum ante ipsum primis in faucibus orci luctus
                          et ultices posuerre cubilia Curao. Donec velit neque,
                          auctor sit amet aliquam vel, ulamcorper sit amet.
                        </p>
                      </div>
                    </div>
                  </div>
                  <!--SIDE ARTICLE-->
                  <div class="col-4 d-flex flex-column">
                    <div>
                      <!--FIRST CARD-->
                      <div class="card">
                        <div class="card-body">
                          <figure>
                            <img
                              src="../assets/images/thumb-13-2x-320x202.jpg"
                              alt="thumb-13"
                              class="img-fluid"
                            />
                          </figure>
                          <h5>What's On Your Booklist</h5>
                          <address class="txt-small">
                            October 24th, 2019 | 0 Comments
                          </address>
                        </div>
                      </div>
                    </div>
                    <div>
                      <!--SECOND CARD-->
                      <div class="card">
                        <div class="card-body">
                          <figure>
                            <img
                              src="../assets/images/thumb-08-2x-320x202.jpg"
                              alt="thumb-13"
                              class="img-fluid"
                            />
                          </figure>
                          <h5>Instanbul Travel Guide</h5>
                          <address class="txt-small">
                            October 24th, 2019 | 0 Comments
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
  name: "Articles",
};
</script>

<style></style>
