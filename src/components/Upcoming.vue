<template>
  <div class="container-fluid bgDawnPink mt-4">
    <div class="row p-4">
      <div class="col">
        <div class="container w-75">
          <div class="row">
            <!--EVENT HEAD-->
            <div class="col-12 text-center">
              <h1 class="dm-serif">Upcoming Events</h1>
              <h4 class="cornFlowerBlue pb-4">Meet the Author</h4>
            </div>
            <!--FIRST EVENT CARD-->
            <div class="col-4 pb-55">
              <div class="card h-100" style="width: 18rem;">
                <img
                  src="../assets/images/event-05.jpg"
                  class="card-img-top"
                  alt="event-05"
                />
                <div class="card-body">
                  <h5 class="card-title text-center">Chicago Book Signing</h5>
                  <hr />
                  <p class="card-text text-center osloGray">
                    Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.
                    Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a
                    nulla.
                  </p>
                </div>
              </div>
            </div>
            <!--SECOND EVENT CARD-->
            <div class="col-4 pb-55">
              <div class="card h-100" style="width: 18rem;">
                <img
                  src="../assets/images/event-04.jpg"
                  class="card-img-top"
                  alt="event-04"
                />
                <div class="card-body">
                  <h5 class="card-title text-center">
                    Meet & Greet With Amanda
                  </h5>
                  <hr />
                  <p class="card-text text-center osloGray">
                    Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.
                    Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a
                    nulla.
                  </p>
                </div>
              </div>
            </div>
            <!--THIRD EVENT CARD-->
            <div class="col-4 pb-55">
              <div class="card h-100" style="width: 18rem;">
                <img
                  src="../assets/images/event-07.jpg"
                  class="card-img-top"
                  alt="event-05"
                />
                <div class="card-body">
                  <h5 class="card-title text-center">Open Book: Dialogues</h5>
                  <hr />
                  <p class="card-text text-center osloGray">
                    Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.
                    Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a
                    nulla.
                  </p>
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
  name: "Upcoming",
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/_vars.scss";

.bgDawnPink {
  min-height: 200px;
}

.card:hover {
  cursor: pointer;
  p {
    color: $scorpion;
  }
  img {
    filter: sepia(0.4);
  }
}
</style>
