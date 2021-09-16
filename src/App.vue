<template>
  <div id="app">
    <Header />
    <Moreabout />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Moreabout from './components/Moreabout.vue';

export default {
  name: 'App',
  components: {
    Header,
    Moreabout
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css");
@import url('https://fonts.googleapis.com/css2?family=Kristi&display=swap');
@import "assets/scss/style.scss"


</style>
