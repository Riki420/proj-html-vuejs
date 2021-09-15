<template>
<!--Header-->
  <header>
      <div class="container">
          <div class="row">
              <!--LOGO-->
              <div class="col">
                  <figure>
                      <img src="../assets/images/author-logo-round-200x205.png" alt="logo" class="img-fluid">
                  </figure>
              </div>
          </div>
      </div>
  </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>
    header{
        background-image: url('../assets/images/footer-3.jpg');
        background-size: cover;
        background-position: top;
        background-repeat: no-repeat;
        height: 500px;

    }

</style>