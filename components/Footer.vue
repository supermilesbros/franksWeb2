<template>
    <div>
      <footer class="site-footer">
        <div class="site-footer_farm_image"><img src="/assets/images/resources/site-footer-farm.png"
                                                 alt="Farm Image"></div>
        <div class="container">
          <div class="row no-gutters">
            <div class="col-xl-3 col-lg-3 col-md-6">
              <div class="footer-widget__column footer-widget__about wow fadeInUp" data-wow-delay="100ms">
                <div class="footer-widget__title">
                  <h3>About</h3>
                </div>
                <div class="footer-widget_about_text">
                  <p>TURNING THE EYES OF INDY TOWARDS THE NATURAL BEAUTY
                      OF OUR WATERWAYS
                      THROUGH PADDLING EXPERIENCES</p>
                </div>
                <form>
                  <div class="footer_input-box">
                    <input type="Email" placeholder="Email Address">
                    <button type="submit" class="button"><i class="fa fa-check"></i></button>
                  </div>
                </form>
              </div>
            </div>
            <div class="col-xl-3 col-lg-3 col-md-6">
              <div class="footer-widget__column footer-widget__link wow fadeInUp" data-wow-delay="200ms">
                <div class="footer-widget__title">
                  <h3>Explore</h3>
                </div>
                <ul class="footer-widget__links-list list-unstyled">
                  <li><a href="#">About Us</a></li>
                  <li><a href="#">Our Boats</a></li>
                  <li><a href="#">Our Friends</a></li>
                  <li><a href="#">Canoes</a></li>
                  <li><a href="#">Kayaks</a></li>
                  <li><a href="#">Paddleboards</a></li>
                </ul>
              </div>
            </div>
            <div class="col-xl-3 col-lg-3 col-md-6">
              <div class="footer-widget__column footer-widget__link wow fadeInUp" data-wow-delay="200ms">
                <div class="footer-widget__title">
                  <h3>Quick Links</h3>
                </div>
                <ul class="footer-widget__links-list list-unstyled">
                  <li><a href="#">Cancelation Policy</a></li>
                  <li><a href="#">FAQ</a></li>
                  <li><a href="#">River Map</a></li>
                </ul>
              </div>
            </div>
            <div class="col-xl-3 col-lg-3 col-md-6">
              <div class="footer-widget__column footer-widget__contact wow fadeInUp" data-wow-delay="300ms">
                <div class="footer-widget__title">
                  <h3>Contact</h3>
                </div>
                <div class="footer-widget_contact">
                  <p>Greater Indianapolis<br>Area</p>
                  <a href="mailto:admin@frankslivery.com">admin@frankslivery.com</a><br>
                  <a href="tel:666-888-0000">260-226-3075</a>
                  <div class="site-footer__social">
                    <a href="#"><i class="fab fa-facebook-square"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-dribbble"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </footer>

      <div class="site-footer_bottom">
        <div class="container">
          <div class="site-footer_bottom_copyright">
            <p>@ All copyright 2023, <a target="_blank" href="https://www.supermilesbros.com">supermilesbros.com</a></p>
          </div>
          <div class="site-footer_bottom_menu">
            <ul class="list-unstyled">
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Terms of Use</a></li>
            </ul>
          </div>
        </div>
      </div>

      <a @click="scrollTop" href="#" class="scroll-to-target scroll-to-top" :style="`display: ${scrollBtn ? 'block' : 'none'}`"><i class="fa fa-angle-up"></i></a>

    </div>
</template>

<script>
    export default {
      name: "Footer",
      data(){
        return {
          scrollBtn: false
        }
      },
      mounted() {
        window.addEventListener('scroll', this.handleScroll);
      },

      methods: {

        handleScroll () {

          if (window.scrollY > 70) {
            this.scrollBtn = true
          }
          else if (window.scrollY < 70) {
            this.scrollBtn = false
          }
        },

        scrollTop () {
          window.scrollTo(0, 0);
        }

      }
    }
</script>

<style scoped>

</style>
