<template>
  <div>
    <NavFive />
    <PageHeader title="Contact" />
    <ContactTwo />
    <GMap />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import ContactTwo from "../components/ContactTwo";
  import GMap from "../components/GMap";
  export default {
    components: {
      GMap,
      ContactTwo,
      Footer,
      PageHeader,
      NavFive
    },
    head(){
      return {
        title: "Frank's  | Contact"
      }
    }
  }
</script>
