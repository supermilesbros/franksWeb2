<template>
  <div>
    <NavFive />
    <CanoeDetail />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import CanoeDetail from "../components/CanoeDetail";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      CanoeDetail,
      NavFive
    },
    data() {
      return {
      }
    },
    head(){
      return {
        title: "Frank's  | Our Canoes"
      }
    }
  }
</script>
