<template>
  <div>
    <NavFive />
    <PageHeader title="Our Kayak" />
    <KayakDetail />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeader from "../components/PageHeader";
  import KayakDetail from "../components/KayakDetail";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      PageHeader,
      KayakDetail,
      NavFive
    },
    head(){
      return {
        title: "Frank's  | Our Kayak"
      }
    }
  }
</script>
