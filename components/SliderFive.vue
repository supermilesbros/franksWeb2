<template>
  <section class="banner-section banner-five">
    <div class="banner-carousel five owl-theme owl-carousel">
      <no-ssr>
        <carousel :items="1" :autoplay="false" :autoplayTimeout="5000" :nav="false">
      <!-- Slide Item -->
      <div class="slide-item">
        <div class="banner_five_bg"
             style="background-image: url(/assets/images/main-slider/banner-five-bg.jpg)"></div>
        <div class="container container-fix">
          <div class="row content-box">
            <div class="col-xl-5 content">
              <div class="inner">
                <div style="font-family: CocoGoose-Pro-Italic" class="large-title">Welcome<br>to Your<br> Next Adventure</div>
                <p>Indianapolis’ leading provider of canoe, kayak and stand-up paddleboard rentals, tailored experiences and instruction.</p>
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
        <div class="banner_five_bg"
             style="background-image: url(/assets/images/main-slider/banner-five-bg2.jpg)"></div>
        <div class="container">
          <div class="row content-box">
            <div class="col-xl-5 content">
              <div class="inner">
                <div class="large-title">organic &<br> agriculture<br> Forming</div>
                <p>An qualisque constituam cum. Agam unum disputando ius et, mel id postea voluptua,
                  et vel assum graece feugait.</p>
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
        <div class="banner_five_bg"
             style="background-image: url(/assets/images/main-slider/banner-five-bg3.jpg)"></div>
        <div class="container">
          <div class="row content-box">
            <div class="col-xl-5 content">
              <div class="inner">
                <div class="large-title">organic &<br> agriculture<br> Forming</div>
                <p>An qualisque constituam cum. Agam unum disputando ius et, mel id postea voluptua,
                  et vel assum graece feugait.</p>
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
        name: "SliderFive"
    }
</script>

<style scoped>
.container-fix {
  max-width: 1500px;
}
</style>
