<template>
  <div class="container py-4">
    <div class="row">
      <div class="col">
        <div class="container w-75">
          <div class="row pb-4">
            <div class="col-12 text-center pb-4">
              <h2 class="dm-serif">Dig A Little Deeper Into Damon Vaughn</h2>
              <p class="keppel pb-2">FIND OUT MORE ABOUT THE AUTHOR HIMSELF</p>
            </div>
            <div class="col-12 col-md-4 col-lg-4 mt-2">
              <div class="box-1 round-right">
                <h4 class="text-white">About Me</h4>
                <hr class="bg-white w-25" />
                <p class="keppel">Vestibulum ante ipsum primis</p>
              </div>
            </div>
            <div class="col-12 col-md-4 col-lg-4 mt-2">
              <div class="box-3 round-right">
                <h4 class="text-white">About Me</h4>
                <hr class="bg-white w-25" />
                <p class="keppel">Vestibulum ante ipsum primis</p>
              </div>
            </div>
            <div class="col-12 col-md-4 col-lg-4 mt-2">
              <div class="box-4 round-right">
                <h4 class="text-white">About Me</h4>
                <hr class="bg-white w-25" />
                <p class="keppel">Vestibulum ante ipsum primis</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Littledeep",
};
</script>

<style lang="scss" scoped>
.box-1 {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("../assets/images/box-1.jpg");
  background-position: left;
  background-size: cover;
  min-height: 360px;
  display: flex;
  flex-direction: column;
  align-content: center;
  align-items: center;
  justify-content: flex-end;
  text-align: center;
  &:hover {
    box-shadow: 2px 2px 4px 2px rgba(0, 0, 0, 0.2);
    cursor: pointer;
  }
}
.box-3 {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("../assets/images/box-3.jpg");
  background-position: left;
  background-size: cover;
  min-height: 360px;
  display: flex;
  flex-direction: column;
  align-content: center;
  align-items: center;
  justify-content: flex-end;
  text-align: center;
  &:hover {
    box-shadow: 2px 2px 4px 2px rgba(0, 0, 0, 0.2);
    cursor: pointer;
  }
}
.box-4 {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("../assets/images/box-4.jpg");
  background-position: left;
  background-size: cover;
  min-height: 360px;
  display: flex;
  flex-direction: column;
  align-content: center;
  align-items: center;
  justify-content: flex-end;
  text-align: center;
  &:hover {
    box-shadow: 2px 2px 4px 2px rgba(0, 0, 0, 0.2);
    cursor: pointer;
  }
}
</style>
