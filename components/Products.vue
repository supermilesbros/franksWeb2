<template>
  <section class="product">
    <div class="container">
      <div class="row">
        <!--End Sidebar Wrapper-->
        <div class="col-xl-12 col-lg-12">
          <div class="product-items">
            <div class="row">
            </div>
            <div class="all_products">
              <div class="row">
                <div class="col-xl-4 col-lg-4 col-md-6">
                  <div class="all_products_single text-center">
                    <div class="all_product_item_image">
                      <img src="/assets/images/shop/shop_product_1.jpg" alt="">
                      <div class="all_product_hover">
                        <div class="all_product_icon">
                          <nuxt-link to="/cart"><span class="icon-shopping-cart"></span></nuxt-link>
                        </div>
                      </div>
                    </div>
                    <h4><nuxt-link to="/product-detail">T-Shirt</nuxt-link></h4>
                    <p>$19.99</p>
                  </div>
                </div>
                <div class="col-xl-4 col-lg-4 col-md-6">
                  <div class="all_products_single text-center">
                    <div class="all_product_item_image">
                      <img src="/assets/images/shop/shop_product_2.jpg" alt="">
                      <div class="all_product_hover">
                        <div class="all_product_icon">
                          <nuxt-link to="/cart"><span class="icon-shopping-cart"></span></nuxt-link>
                        </div>
                      </div>
                    </div>
                    <h4><nuxt-link to="/product-detail">Beanie</nuxt-link></h4>
                    <p>9.99</p>
                  </div>
                </div>
                <div class="col-xl-4 col-lg-4 col-md-6">
                  <div class="all_products_single text-center">
                    <div class="all_product_item_image">
                      <img src="/assets/images/shop/shop_product_3.jpg" alt="">
                      <div class="all_product_hover">
                        <div class="all_product_icon">
                          <nuxt-link to="/cart"><span class="icon-shopping-cart"></span></nuxt-link>
                        </div>
                      </div>
                    </div>
                    <h4><nuxt-link to="/product-detail">Trucker Hat</nuxt-link></h4>
                    <p>$9.99</p>
                  </div>
                </div>
                <div class="col-xl-4 col-lg-4 col-md-6">
                  <div class="all_products_single text-center">
                    <div class="all_product_item_image">
                      <img src="/assets/images/shop/shop_product_4.jpg" alt="">
                      <div class="all_product_hover">
                        <div class="all_product_icon">
                          <nuxt-link to="/cart"><span class="icon-shopping-cart"></span></nuxt-link>
                        </div>
                      </div>
                    </div>
                    <h4><nuxt-link to="/product-detail">T-Shirt</nuxt-link></h4>
                    <p>$2.99</p>
                  </div>
                </div>
                <div class="col-xl-4 col-lg-4 col-md-6">
                  <div class="all_products_single text-center">
                    <div class="all_product_item_image">
                      <img src="/assets/images/shop/shop_product_5.jpg" alt="">
                      <div class="all_product_hover">
                        <div class="all_product_icon">
                          <nuxt-link to="/cart"><span class="icon-shopping-cart"></span></nuxt-link>
                        </div>
                      </div>
                    </div>
                    <h4><nuxt-link to="/product-detail">Beanie</nuxt-link></h4>
                    <p>$6.00</p>
                  </div>
                </div>
                <div class="col-xl-4 col-lg-4 col-md-6">
                  <div class="all_products_single text-center">
                    <div class="all_product_item_image">
                      <img src="/assets/images/shop/shop_product_6.jpg" alt="">
                      <div class="all_product_hover">
                        <div class="all_product_icon">
                          <nuxt-link to="/cart"><span class="icon-shopping-cart"></span></nuxt-link>
                        </div>
                      </div>
                    </div>
                    <h4><nuxt-link to="/product-detail">Trucker Hat</nuxt-link></h4>
                    <p>$5.98</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "Products"
    }
</script>

<style scoped>

</style>
