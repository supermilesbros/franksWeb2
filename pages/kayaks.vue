<template>
  <div>
    <NavFive />
    <PageHeader title="Product Detail" />
    <ProductDetail />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeader from "../components/PageHeader";
  import ProductDetail from "../components/ProductDetail";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      PageHeader,
      ProductDetail,
      NavFive
    },
    head(){
      return {
        title: "Agrikol  | Product Detail"
      }
    }
  }
</script>
