<template>
  <section class="banner_four_section">

    <div class="banner-carousel-four owl-theme owl-carousel">
      <no-ssr>
        <carousel :items="1" :autoplay="false" :autoplayTimeout="5000" :nav="false">
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="image-layer" style="background-image: url(/assets/images/main-slider/home-hero3.jpg);">
        </div>
        <div class="auto-container">
          <div class="content-box">
            <div class="content text-center">
              <div class="inner">
                <h1><span style="font-family: CocoGoose-Pro-Italic">Frank's Paddlesports Livery</span></h1>
                <!-- <h1 style="font-size: 2.5em;">at The Parks Alliance of Indianapolis</h1> -->
                <div style="padding-top: 35px;" class="link-box">
                  <!-- <a href="/" target="_blank" class="thm-btn">Discover More</a> -->
                  <div class="thm-btn">Coming Soon</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Slide Item -->

      <!-- Slide Item -->
        </carousel>
      </no-ssr>
    </div>
  </section>
</template>

<script>
    export default {
      name: "SliderFour"
    }
</script>

<style scoped>

</style>
