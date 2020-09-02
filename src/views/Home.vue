<template>
  <div class="home">
   <Navbar></Navbar>
   
   <Hero/>
   <!-- <Product-list class='margin'></Product-list> -->
    <product/>
   <div class="container h-100">
        <div class="row p-5 h-80 justify-content-center align-items-center">
          <div class="col-md-5">
            <img src="/img/svg/product.jpg" alt="" width="300" height="400">
          </div>
          <div class="col-md-4">
              <h6>Learn more about</h6>
              <h3>Radiant Skin Collection</h3>
            <p>
              <a></a>
            </p>
             <a class="btn custom-btn btn-outline-primary mr-4" href="https://www.facebook.com/radiantskincollection">Click Here </a>
          </div>
        </div>
      </div>

  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Hero from "@/components/Hero.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,Hero
  }
};
</script>
<style lang="scss" scoped>
.margin{
  margin-top: 10rem;
}
</style>
