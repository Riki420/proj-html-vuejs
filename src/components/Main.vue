<template>
  <div id="main">
    <Moreabout />
    <Logotan />
    <Audible />
    <Testimonial />
  </div>
</template>

<script>
import Moreabout from "./Moreabout.vue";
import Logotan from "./Logotan.vue";
import Audible from "./Audible.vue";
import Testimonial from "./Testimonial.vue";
export default {
  name: "Main",
  components: {
    Moreabout,
    Logotan,
    Audible,
    Testimonial,
  },
};
</script>

<style></style>
