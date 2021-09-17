<template>
  <div class="container-fluid bg-foot mt-4">
    <div class="row p-4 justify-content-center align-items-center">
      <div class="col">
        <figure>
          <img
            src="../assets/images/author-logo-round-small.png"
            alt="logo-foot"
            class="img-fluid"
          />
        </figure>
      </div>
      <div class="col">
        <ul class="text-white">
          <li><h4>TITOLO</h4></li>
          <li>TESTO</li>
          <li>TESTO</li>
          <li>TESTO</li>
          <li>TESTO</li>
        </ul>
      </div>
      <div class="col">
        <ul class="text-white">
          <li><h4>TITOLO</h4></li>
          <li>TESTO</li>
          <li>TESTO</li>
          <li>TESTO</li>
          <li>TESTO</li>
        </ul>
      </div>
      <div class="col">
        <ul class="text-white">
          <li><h4>TITOLO</h4></li>
          <li>TESTO</li>
          <li>TESTO</li>
          <li>TESTO</li>
          <li>TESTO</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss">
.bg-foot {
  background-image: url("../assets/images/footer-3.jpg");
  background-position: top;
  background-size: cover;
  min-height: 400px;
}
</style>
