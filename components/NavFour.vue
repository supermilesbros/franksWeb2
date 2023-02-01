<template>
  <div class="site_header__header_four_wrap">
    <div class="topbar-one topbar_four">
      <div class="container">
        <div class="topbar-one__left">
          
        </div>
        <div class="topbar-one__middle">
          <a href="/" class="main-nav__logo">
            <img
              src="/assets/images/resources/frankFull-white.png"
              class="main-logo"
              style="height: 150px;"
              alt="Awesome Image"
            />
          </a>
        </div>
        <!-- <div class="topbar-one__right">
          <a href="https://www.parks-alliance.org/" target="_blank" class="main-nav__logo">
            <img
              src="/assets/images/resources/TPA_White.png"
              class="main-logo"
              style="height: 100px;"
              alt="Awesome Image"
            />
          </a>
        </div> -->
      </div>
    </div>

    <header class="main-nav__header-one main-nav__header-four">
      
    </header>
  </div>
</template>

<script>
import { mapMutations } from "vuex";

export default {
  name: "NavFour",
  data() {
    return {
      sticky: false,
      mobileToggle: false,
    };
  },
  computed: {
    searchPopup() {
      return this.$store.state.searchPopupStatus;
    },
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      if (window.scrollY > 70) {
        this.sticky = true;
      } else if (window.scrollY < 70) {
        this.sticky = false;
      }
    },
    ...mapMutations({
      searchPopupStatusChange: "changeSearchPopupStatus",
    }),
  },
};
</script>


