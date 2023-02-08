<template>
  <div class="site_header__header_five_wrap">
    <div class="topbar-three topbar-five">
      <div class="container-box">
        <div class="topbar_three_content clearfix">
          <div class="logo-box-three logo-box-five float-left">
            <a href="/" class="main-nag__logo">
              <img style="width: 50%;" src="/assets/images/franks/franks-logo-menu-2.png" alt="">
            </a>
          </div>

          <div class="topbar_three_nav_box float-left">
            <nav :class="`header-navigation stricky clearfix ${sticky ? 'stricked-menu stricky-fixed' : ''}`">
              <div class="container">
                <div class="main_nav_header_three_content five clearfix">
                  <div class="mobile_menu_icon_three five">
                    <a href="#" class="side-menu__toggler">
                      <i @click="mobileToggle = !mobileToggle" class="fa fa-bars"></i>
                    </a>
                  </div>
                  <div class="main-nav__main-navigation five float-left">
                    <ul class=" main-nav__navigation-box">
                      <li>
                        <nuxt-link to="/aboutus">About</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/parksAlliance">Our Friends</nuxt-link>
                      </li>
                      <li class="dropdown">
                        <nuxt-link to="#">Our Boats</nuxt-link>
                        <ul>
                          <li><nuxt-link to="/canoes">Canoes</nuxt-link></li>
                          <li><nuxt-link to="/kayaks">Kayaks</nuxt-link></li>
                          <li><nuxt-link to="/paddleboards">Stand-Up Paddleboards</nuxt-link></li>
                        </ul><!-- /.sub-menu -->
                      </li>
                      <li>
                        <nuxt-link to="/product">Shop</nuxt-link>
                      </li>
                      <li>
                        <nuxt-link to="/contact">Contact Us</nuxt-link>
                      </li>
                    </ul>
                  </div>

                </div>
              </div>
            </nav>
          </div>
          <div class="topbar_three_right_box five">
            <div class="topbar-one__social">
              <a href="#"><i class="fab fa-facebook-square"></i></a>
              <a href="#"><i class="fab fa-twitter"></i></a>
              <a href="#"><i class="fab fa-instagram"></i></a>
              <a href="#"><i class="fab fa-dribbble"></i></a>
            </div>
          </div>

        </div>
      </div>
    </div>

    <nav class="mobile-nav__container" :style="`display: ${mobileToggle ? 'block' : 'none'}`">
      <!-- content is loading via js -->

      <ul class="main-nav__navigation-box">
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/aboutus">About</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/parksAlliance">Our Friends</nuxt-link>
        </li>
        <li class="dropdown">
          <div class="menu-holder">Our Boats<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
          <ul>
            <li><nuxt-link to="/canoes">Canoes</nuxt-link></li>
            <li><nuxt-link to="/kayaks">Kayaks</nuxt-link></li>
            <li><nuxt-link to="/paddleboards">Stand-Up Paddleboards</nuxt-link></li>
          </ul><!-- /.sub-menu -->
        </li>
        <li>
          <nuxt-link to="/shop">Shop</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/contact">Contact Us</nuxt-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
  export default {
    name: "NavFive",
    data(){
      return {
        sticky: false,
        mobileToggle: false
      }
    },
    mounted() {
      window.addEventListener('scroll', this.handleScroll);
    },
    methods: {

      handleScroll() {
        if (window.scrollY > 70) {
          this.sticky = true
        } else if (window.scrollY < 70) {
          this.sticky = false
        }
      },
    }
  }
</script>

<style scoped>

</style>
