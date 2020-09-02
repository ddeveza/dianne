<template>
  <div class="hello">
      <nav class="navbar custom-nav fixed-top navbar-expand-lg navbar-light bg-light" style="background-color:#E77177D;">
            <a class="navbar-brand radiant radiant" >Radiant Skin Collection</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                <li class="nav-item ">
                <router-link to="/" class="nav-link" >Home </router-link>
                </li>
                <li class="nav-item">
                   <router-link to="/about"  class="nav-link" >About</router-link>
                </li>
                
               
                </ul>
                <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-secondary my-2 my-sm-0" type="submit">Login</button>
                </form>
            </div>
        </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
      @media (min-width: 992px) { 
    
    .navbar.custom-nav{
      padding-top:16px;
      padding-bottom:16px;
      background-color: #eb798c !important;
    }

   }

   .radiant{
        font-family: Vollkorn; 
        font-size: 30px;
        font-style: italic;
        font-weight: 700; 
        line-height: 30px;
         text-decoration: underline ;
   }
  

</style>
