<template>
  <section class="bx-testimonial">
    <div class="bx-testimonial_bg" style="background-image: url(/assets/images/testimonials/bx-testi-bg2.png)">
    </div>
    <div class="container">
      <div class="block-title text-center">
        <p class="text-orange">our insiration</p>
        <h3>Learning from the water</h3>
        <div class="leaf">
          <img src="/assets/images/resources/paddle.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-12">
          <div class="bx_testimonial_slider">
            <div class="slider-pager">
              
            </div>

            <ul class="slider-content clearfix bxslider list-unstyled text-center">
              <no-ssr>
                <carousel :items="1" :autoplay="true" :autoplayTimeout="8000" :nav="false" :dots="false">
              <li>
                <div class="bx_testimonial_single clearfix">
                  <div class="bx_testimonial_text">
                    <p class="quote-text">&quot;The care of rivers is not a question of rivers but of the human heart.&quot;</p>
                    <h3>Shozo Tanaka</h3>
                    <h6 class="text-orange">Japan's first conservationist</h6>
                  </div>
                </div>
              </li>
              <li>
                <div class="bx_testimonial_single clearfix">
                  <div class="bx_testimonial_text">
                    <p class="quote-text">&quot;A river is more than an amenity, it is a treasure. It offers a necessity of life that must be rationed among those who have power over it. &quot;</p>
                    <h3>Oliver Wendell Holmes</h3>
                    <h6 class="text-orange">Associate Justice</h6>
                  </div>
                </div>
              </li>
              <li>
                <div class="bx_testimonial_single clearfix">
                  <div class="bx_testimonial_text">
                    <p class="quote-text">&quot;Thousands have lived without love, not one without water.&quot;</p>
                    <h3>W. H. Auden</h3>
                    <h6 class="text-orange">British-American Poet</h6>
                  </div>
                </div>
              </li>
                </carousel>
              </no-ssr>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "TestimonialFour"
    }
</script>

<style scoped>
.text-orange {
  color: var(--thm-base)
}
.quote-text {
  font-size: 2rem;
  font-weight: 700;
}
</style>
