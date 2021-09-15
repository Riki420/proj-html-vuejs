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
              <!--NAVBAR-->
              <div class="col-7">
                  <ul class="nav">
                      <li class="nav-item"><a href="#" class="nav-link py-4 text-white selected">Home</a></li>
                      <li class="nav-item"><a href="#" class="nav-link text-white py-4">About Me</a></li>
                      <li class="nav-item"><a href="#" class="nav-link text-white py-4">Testimonials</a></li>
                      <li class="nav-item"><a href="#" class="nav-link text-white py-4">My Blog</a></li>
                      <li class="nav-item"><a href="#" class="nav-link text-white py-4">Meetups</a></li>
                      <li class="nav-item"><a href="#" class="nav-link text-white py-4">Shop</a></li>
                      <li class="nav-item"><a href="#" class="nav-link text-white py-4">Contact Me</a></li>
                      <li class="nav-item"><a href="#" class="nav-link text-white py-4"><i class="bi bi-cart-fill"></i></a></li>
                  </ul>
              </div>
          </div>
          <div class="row ps-4">
              <div class="col-6">
                  <h1 class="handwrite-big">Damon Vaughn</h1>
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
@import "../assets/scss/_vars.scss";
    header{
        background-image: url('../assets/images/hero-07-2x.jpg');
        background-size: cover;
        background-position: top;
        background-repeat: no-repeat;
        min-height: 500px;
        .nav-link{
            &:hover{
                border-top: 4px solid $saffron;
                color: $saffron;
            }
        }
        .selected{
            border-top: 4px solid $saffron;
            color: $saffron;
        }
        
        
    }

</style>