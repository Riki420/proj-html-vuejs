<template>
  <div class="container-fluid bgDawnPink pt-55 pb-55">
    <div class="row">
      <div class="col">
        <div class="container w-75">
          <div class="row">
            <!--EVENT HEAD-->
            <div class="col-12 text-center">
              <h3 class="dm-serif">Upcoming Events</h3>
              <p class="cornFlowerBlue pb-4">Meet the Author</p>
            </div>
            <!--EVENT CARD-->
            <div
              class="col col-md-4 col-lg-4 pb-55"
              v-for="event in events"
              :key="event.id"
            >
              <div class="card h-100" style="width: 18rem;">
                <img
                  :src="event.image"
                  class="card-img-top"
                  :alt="event.name"
                />
                <div class="card-body">
                  <h5 class="card-title text-center">{{ event.name }}</h5>
                  <hr />
                  <p class="card-text text-center osloGray">
                    {{ event.info }}
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
  name: "Events",
  data() {
    return {
      events: [
        {
          id: 1,
          name: "Chicago Book Signing",
          image: "../assets/images/event-05.jpg",
          info:
            " Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a nulla.",
        },
        {
          id: 2,
          name: "Meet & Greet With Amanda",
          image: "../assets/images/event-04.jpg",
          info:
            " Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a nulla.",
        },
        {
          id: 3,
          name: "Open Book: Dialogues",
          image: "../assets/images/event-07.jpg",
          info:
            " Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a nulla.",
        },
      ],
    };
  },
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
