<template>
  <div>
    <NavFive />
    <PageHeaderCanoes title="Our Canoes" />
    <CanoeDetail />
    <!-- <Footer /> -->
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeaderCanoes from "../components/PageHeaderCanoes";
  import CanoeDetail from "../components/CanoeDetail";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      PageHeaderCanoes,
      CanoeDetail,
      NavFive
    },
    head(){
      return {
        title: "Frank's  | Our Canoes"
      }
    }
  }
</script>
