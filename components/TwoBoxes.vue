<template>
  <section class="two_boxes">
    <div class="container_fullwidth">
      <div class="row">
        <div class="col-xl-6">
          <div class="left_box">
            <h2>Learn more about how you can protect our waterways</h2>
            <div class="left_box_btn">
              <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
            </div>
          </div>
        </div>
        <div class="col-xl-6">
          <div class="right_box">
            <h2>Sign up for our newsletter<br>& stay up to date</h2>
            <div class="right_box_btn">
              <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "TwoBoxes"
    }
</script>

<style scoped>

</style>
