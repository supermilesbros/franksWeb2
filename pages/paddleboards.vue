<template>
  <div>
    <NavFive />
    <PageHeader title="Stand-Up Paddleboards" />
    <SupDetail />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeader from "../components/PageHeader";
  import SupDetail from "../components/SupDetail";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      PageHeader,
      SupDetail,
      NavFive
    },
    head(){
      return {
        title: "Frank's  | Stand-Up Paddleboards"
      }
    }
  }
</script>
