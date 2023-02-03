<template>
  <div>
    <NavFive />
    <PageHeader title="Merch" />
    <Products />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import Products from "../components/Products";
  export default {
    components: {
      Products,
      Footer,
      PageHeader,
      NavFive
    },
    head(){
      return {
        title: "Agrikol  | Products"
      }
    }
  }
</script>
