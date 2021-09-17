<template>
  <div id="main">
    <Moreabout />
    <Logotan />
    <Audible />
    <Testimonial />
    <Upcoming />
    <Newsletter />
    <Articles />
  </div>
</template>

<script>
import Moreabout from "./Moreabout.vue";
import Logotan from "./Logotan.vue";
import Audible from "./Audible.vue";
import Testimonial from "./Testimonial.vue";
import Upcoming from "./Upcoming.vue";
import Newsletter from "./Newsletter.vue";
import Articles from "./Articles.vue";
export default {
  name: "Main",
  components: {
    Moreabout,
    Logotan,
    Audible,
    Testimonial,
    Upcoming,
    Newsletter,
    Articles,
  },
};
</script>

<style></style>
