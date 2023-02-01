<template>
  <div>
    <NavFive />
    <PageHeader title="Our Friends" />
    <ProjectPage />
    <Footer />
  </div>
</template>

<script>

  import NavFive from "../components/NavFive";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import ProjectPage from "../components/ProjectPage";
  export default {
    components: {
      ProjectPage,
      Footer,
      PageHeader,
      NavFive
    },
    head(){
      return {
        title: "Frank's  | Our Friends"
      }
    }
  }
</script>
