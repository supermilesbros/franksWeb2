<template>

  <section class="page-header" style="background-image: url(/assets/images/backgrounds/page-header-contact.jpg);">
    <div class="container">
      <h2 class="header-text">{{ title }}</h2>
      <ul class="thm-breadcrumb list-unstyled">
        <li><nuxt-link to="/canoes">Prospecteur 16</nuxt-link></li>
        <li><span>Huron 16</span></li>
      </ul>
    </div>
  </section>

</template>

<script>
  export default {
    name: "PageHeader",
    props: {
      title: {
        type: String
      }
    }

  }
</script>

<style scoped>
.header-text {
  color: var(--thm-accent);
  text-shadow: 1px 1px #1a1b1e;
}
</style>
