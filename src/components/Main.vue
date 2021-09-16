<template>
  <div id="main">
    <Moreabout />
    <Logotan />
    <Audible />
  </div>
</template>

<script>
import Moreabout from "./Moreabout.vue";
import Logotan from "./Logotan.vue";
import Audible from "./Audible.vue";
export default {
  name: "Main",
  components: {
    Moreabout,
    Logotan,
    Audible,
  },
};
</script>

<style></style>
