<template>
  <div id="main">
    <Moreabout />
    <Logotan />
    <Audible />
    <Testimonial />
    <Upcoming />
    <Newsletter />
  </div>
</template>

<script>
import Moreabout from "./Moreabout.vue";
import Logotan from "./Logotan.vue";
import Audible from "./Audible.vue";
import Testimonial from "./Testimonial.vue";
import Upcoming from "./Upcoming.vue";
import Newsletter from "./Newsletter.vue";
export default {
  name: "Main",
  components: {
    Moreabout,
    Logotan,
    Audible,
    Testimonial,
    Upcoming,
    Newsletter,
  },
};
</script>

<style></style>
