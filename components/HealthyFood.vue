<template>
  <section class="healthy_food">
    <div class="healthy_food_bg" style="background-image: url(/assets/images/resources/helathy_food_bg.png)">
    </div>
    <div class="container">
      <div class="block-title text-left">
        <p class="text-orange">Frank's Paddlesports</p>
        <h3 class="mission-text">Our Mission Statement</h3>
        <div class="leaf">
          <img src="/assets/images/resources/paddle.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-6">
          <div class="healthy_food_text">
            <p>Our mission is to be Indianapolis’ leading provider of canoe, kayak and stand-up paddleboard rentals, tours and instruction. We aim to explore new
                opportunities that build the river community, provide equitable river access and
                create environmental sustainability using our core competencies to gain an
                advantageous market position.
            </p>
          </div>
          
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "HealthyFood"
    }
</script>

<style scoped>
.text-orange {
  color: var(--thm-base)
}
.mission-text {
  text-shadow: 1px 1px #1a1b1e
}
</style>
