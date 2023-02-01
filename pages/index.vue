<template>
  <div>
    <NavFive />
    <SliderFive />
    <ServiceTwo />
    <TestimonialFour />
    <TwoBoxes />
    <HealthyFood />
    <ContactOne />
    <Footer />
  </div>
</template>

<script>
  import NavFive from "../components/NavFive";
  import SliderFive from "../components/SliderFive";
  import ServiceTwo from "../components/ServiceTwo";
  import TestimonialFour from "../components/TestimonialFour";
  import TwoBoxes from "../components/TwoBoxes";
  import HealthyFood from "../components/HealthyFood";
  import ContactOne from "../components/ContactOne";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      ContactOne,
      HealthyFood,
      TwoBoxes,
      TestimonialFour,
      ServiceTwo,
      SliderFive,
      NavFive
    },
    head(){
      return {
        title: "Frank's  | Home"
      }
    }
  }
</script>
