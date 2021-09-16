<template>
  <div id="main">
    <Moreabout />
    <Logotan />
    <Audible />
    <Criticsay />
  </div>
</template>

<script>
import Moreabout from "./Moreabout.vue";
import Logotan from "./Logotan.vue";
import Audible from "./Audible.vue";
import Criticsay from "./Criticsay.vue";
export default {
  name: "Main",
  components: {
    Moreabout,
    Logotan,
    Audible,
    Criticsay,
  },
};
</script>

<style></style>
