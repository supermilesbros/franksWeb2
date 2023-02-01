<template>
  <div>
    <NavFive />
    <PageHeader title="ABOUT US" />
    <TeamOne />
    <BenefitsTwo />
    <CompanySolutions />
    <TestimonialThree />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import TeamOne from "../components/TeamOne";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import BestCompany from "../components/BestCompany";
  import TestimonialThree from "../components/TestimonialThree";
  import BenefitsTwo from "../components/BenefitsTwo";
  import WhyChooseOne from "../components/WhyChooseOne";
  import CompanySolutions from "../components/CompanySolutions";
  export default {
    components: {
      TeamOne,
      CompanySolutions,
      WhyChooseOne,
      BenefitsTwo,
      TestimonialThree,
      BestCompany,
      Footer,
      PageHeader,
      NavFive
    },
    head(){
      return {
        title: "Frank's  | About Us"
      }
    }
  }
</script>
