<template>
  <section class="banner-section banner-one">

    <div class="banner-carousel">
      <!-- Slide Item -->
      <no-ssr>
      <carousel :items="1" :autoplay="false" :nav="false">

        <div class="slide-item">
          <div class="image-layer" style="background-image: url(/assets/images/main-slider/home-hero1.jpg);">
          </div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">The best paddlesports experience</div>
                  <h1>Welcome to<br> Frank's</h1>
                  <div class="link-box">
                    <nuxt-link to="/about" class="thm-btn" style="color: white;">Discover More</nuxt-link>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Slide Item -->
        <div class="slide-item">
          <div class="image-layer" style="background-image: url(/assets/images/main-slider/home-hero2.jpg);">
          </div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">The best Agriculture products</div>
                  <h1>Welcome to<br> Frank's</h1>
                  <div class="link-box">
                    <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Slide Item -->
        <div class="slide-item">
          <div class="image-layer" style="background-image: url(/assets/images/main-slider/home-hero3.jpg);">
          </div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">The best Agriculture products</div>
                  <h1>Welcome to<br> Frank's</h1>
                  <div class="link-box">
                    <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </carousel>
      </no-ssr>
    </div>
  </section>
</template>

<script>

    export default {
      name: "Slider",
      data(){
          return {

          }
      }
    }
</script>

<style scoped>

</style>
