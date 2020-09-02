<template>
  <div class="products" id="products">
      <div class="container">
          <h1 class="text-center p-5">Radiant Skin Collection Products</h1>
          <div class="row">
              
              <div class="col-md-4">
                  <div class="card product-item">
                    <img src="/img/products/product1.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Mix & Match</h5>
                            <p class="card-text">
                                Big set of starter kit, rejuvinating toner replaced with deep cleansing water. ❤
                            </p>
                            <a href="#" class="btn btn-primary">Add to Cart</a>
                        </div>
                    </div>
              </div>

              <div class="col-md-4">
                  <div class="card product-item">
                    <img src="/img/products/product2.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Kenpaku</h5>
                            <p class="card-text">
                              Experience a Healthier, Younger and Beautiful you! Best Japan Glutathione Is Now Here In The Philippines!
                                This is not your ordinary Glutathione, it contains Vitamin C, Collagen and Icystine that will give you whiter skin and glowing skin.
                                    1 bottle contains 62pcs of capsules.
                            </p>
                            <a href="#" class="btn btn-primary">Add to Cart</a>
                        </div>
                    </div>
              </div>

              <div class="col-md-4">
                  <div class="card product-item">
                    <img src="/img/products/product3.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Beauty Mist</h5>
                            <p class="card-text">
                                   Too tired of using your hands just to reapply sunshield?

                                    Say no more with our Beauty Mist!
                                    Just spray whenever you like without a worry you’ll be getting your face some dirt!

                                    Already packed with SPF50!
                                    Also perfect before and after doing make-up!
                                    Also perfect for the whole body!🙀😍

                            </p>
                            <a href="#" class="btn btn-primary">Add to Cart</a>
                        </div>
                    </div>
              </div>
          </div>
      </div>
    
  </div>
</template>

<script>
export default {
  name: "Products",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .products{
        margin-top: 7rem;
        background: #f2f2f2;
        padding-bottom: 3rem;
    }
</style>
