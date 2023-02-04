<template>
  <div>
    <NavFive />
    <PageHeader title="Cart" />
    <Cart />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeader from "../components/PageHeader";
  import Cart from "../components/Cart";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      Cart,
      PageHeader,
      NavFive
    },
    head(){
      return {
        title: "Agrikol  | Cart"
      }
    }
  }
</script>
