<template>
  <div id="main">
    <Moreabout />
    <Logotan />
    <Audible />
    <Testimonial />
    <Events />
    <Newsletter />
    <Littledeep />
    <Articles />
  </div>
</template>

<script>
import Moreabout from "./Moreabout.vue";
import Logotan from "./Logotan.vue";
import Audible from "./Audible.vue";
import Testimonial from "./Testimonial.vue";
import Events from "./Events.vue";
import Newsletter from "./Newsletter.vue";
import Littledeep from "./Littledeep.vue";
import Articles from "./Articles.vue";

export default {
  name: "Main",
  components: {
    Moreabout,
    Logotan,
    Audible,
    Testimonial,
    Events,
    Newsletter,
    Littledeep,
    Articles,
  },
};
</script>

<style></style>
