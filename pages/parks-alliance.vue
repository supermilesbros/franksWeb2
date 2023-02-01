<template>
  <div>
    <NavFive />
    <PageHeader title="The Parks Alliance of Indianapolis" />
    <ProjectDetail />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import ProjectDetail from "../components/ProjectDetail";
  export default {
    components: {
      ProjectDetail,
      Footer,
      PageHeader,
      NavFive
    },
    head(){
      return {
        title: "Frank's  | The Parks Alliance of Indianapolis"
      }
    }
  }
</script>
