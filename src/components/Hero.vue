<template>
    <div class="hero">
        <div class="container h-100">
          <div class="row h-100 justify-content-center align-items-center">
            <div class="col-md-5">
              <div class="hero-content">
                <h1 class="hero-title">
                  Radiant Skin Collection
                </h1>
                <p>
                    Gaano kaganda ang ryx? Umabot napo sa mga bansang Japan, US, Hawaii, Taiwan, Thailand, Australia, Canada, Israel, Qatar, Singapore, New Zealand,  Malaysia, Saudi, UAE, Riyadh, AbuDhabi, Kuwait at Dubai RYX PRODUCTS natin.
                    Who wouldn’t be proud of it?
                </p>
                <div class="hero-btn mt-5">
                    <a class="btn custom-btn btn-info mr-4"  href="https://www.facebook.com/radiantskincollection">Explore</a>
                    <a class="btn custom-btn btn-outline-secondary" href="https://www.facebook.com/radiantskincollection" >Products</a>
                </div>
              </div>
            </div>
            <div class="col-md-7">
                <div class="graphic">
                    <img class='radiantlogo' src="/img/svg/graphic.jpg" alt=""  >
                </div>
            </div>
          </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "Hero",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .hero{
    padding-top: 7rem;
    width: 100%;
    height: 500px;
    text-align: left;
  }
  .radiantlogo{
      border-radius: 50%;
      width : 500px;
      height :450px;
  }
  

</style>
