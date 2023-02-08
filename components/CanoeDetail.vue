<template>
  
    <div>
      <section class="page-header" style="background-image: url(/assets/images/backgrounds/page-header-contact.jpg);">
    <div class="container">
      <h2 class="header-text">OUR Canoes</h2>
      <ul class="thm-breadcrumb list-unstyled">
        <li style="cursor: pointer;" @click="canoe = 'prospector'"><span style="background-color: #fffbce; color: black;">Prospector 16</span></li>
        <li style="cursor: pointer;" @click="canoe = 'huron'"><span @click="canoe == 'huron'">Huron 16</span></li>
      </ul>
    </div>
  </section>
<!-- Prospector Canoe -->
      <section v-show="canoe === 'prospector'" class="product_detail bottom-fix">
        <div class="container">
          <div class="row">
            <div class="col-xl-6 col-lg-6">
              <div class="product_detail_image">
                <img src="/assets/images/shop/product-detai_img-1l.jpg" alt="">
              </div>
            </div>
            <div class="col-xl-6 col-lg-6">
              <div class="product_detail_content">
                <h2>Prospecteur 16</h2>
                <div class="product_detail_text">
                  <p>“The rugged T-Formex hull is great for those who enjoy paddling
                        whitewater or who just want a super tough canoe for everyday usage. Stability,
                        easy tracking, and good maneuverability in rapids are what makes this canoe
                        such a classic.”</p>
                </div>
                <ul class="list-unstyled product_detail_address">
                  <li>Weight : 65lbs</li>
                  <li>Capacity : >1000lbs</li>
                  <li>Seats : Webbed seats</li>
                  <li>Length : 4.9 m (16ft)</li>
                  <li>Width : 89 cm (35″)</li>
                  <li>Depth : 35.6 cm (14″)</li>
                </ul>
                <h3 class="rental-header">rental Pricing</h3>
                <ul class="list-unstyled product_detail_address">
                  <li><span class="text-base">$35</span> for the first hour and <span class="text-base">$20</span> per additional hour for a maximum of 3 hours</li>
                  <li><span class="text-base">$70</span> 3 hour trip from Rocky Ripple to TPA</li>
                  <li><span class="text-base">$85</span> 4.5 hour trip from IAC to TPA</li>
                </ul>
                <p>One child under 10 years of age and under 100 lbs can ride for free in the canoe.
                    Additional seat rental is $10. No children under the age of 2 years allowed and all
                    children must be able to walk unassisted. Parents must provide their own coast guard
                    approved and unexpired personal floatation device for children under the age of 10.</p>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-xl-12">
              <div class="product-tab-box tabs-box">

                <div class="mission-tabs">

                  <!--Tab-->
                  <input type="radio" name="tabsPro" id="tab-one" checked="checked">
                  <label for="tab-one" class="tab-btn">Description</label>
                  <div class="tab">
                    <div class="active-tab">
                      <div class="content">

                        <div class="product-details-content">
                          <div class="desc-content-box">
                            <p class="text-accent">Our  Prospecteur 16 has the lines of the well-known Chestnut Prospector. Ideal for canoeists who want the versatility and capacity of the Prospector shape for day tripping and week-long adventures. The rugged T-Formex hull is great for those who enjoy paddling whitewater or who just want a super tough canoe for everyday usage. Stability, easy tracking, and good maneuverability in rapids are what makes this canoe such a classic.</p>
                            <p class="desc-content-box_bottom text-acccent">T-Formex is a high tech ABS plastic laminate, specially designed for products that require structural memory and a resistance to abrasion and impacts. These characteristics make it the best choice for canoes. </p>
                          </div>
                        </div>

                      </div>
                    </div>
                  </div>

                  <!--Tab-->
                  <input type="radio" name="tabsPro" id="tab-two" >
                  <label for="tab-two" class="tab-btn">History of Canoes</label>
                  <div class="tab">
                    <div class="active-tab">
                      <div class="content">

                        <div class="product-details-content">
                          <div class="desc-content-box">
                            <p class="text-accent">Canoes have been used by indigenous peoples in North America for centuries, likely
                                dating back thousands of years. These early canoes were made of bark or dugout logs,
                                and were used for transportation, hunting, and fishing.</p>
                            <p  class="desc-content-box_bottom text-accent">As European colonizers arrived in North America, they brought with them their own
                                canoe designs, which were often made of wood and covered with animal skins or bark.
                                These canoes were used for exploration and trade, as well as for transportation and
                                hunting.</p>
                            <p  class="desc-content-box_bottom text-accent">In the 19th and early 20th centuries, canoes began to be made of more modern
                                materials such as canvas or aluminum. Today, canoes are made from a variety of
                                materials including fiberglass, plastic, and carbon fiber, and are used for a variety of
                                recreational and competitive purposes, including racing, touring, and wilderness
                                expeditions.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!--Tab-->
                  <input type="radio" name="tabsPro" id="tab-three" >
                  <label for="tab-three" class="tab-btn">Benefits of Canoes</label>
                  <div class="tab">
                    <div class="active-tab">
                      <div class="content">
                        <div class="product-details-content">
                          <div class="desc-content-box">
                            <p class="text-accent">Canoes are generally stable and easy to balance in, making them a good choice for
                                beginners or those who are less comfortable on the water.</p>
                            <p  class="desc-content-box_bottom text-accent">Canoes have a large, open design, which makes them suitable for carrying a lot of gear
                                or multiple passengers.</p>
                            <p  class="desc-content-box_bottom text-accent">Canoes are typically slower than kayaks and SUPs, which can be a benefit for leisurely
                                paddling or fishing trips.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <input type="radio" name="tabsPro" id="tab-four" >
                  <label for="tab-four" class="tab-btn">Drawbacks of Canoes</label>
                  <div class="tab">
                    <div class="active-tab">
                      <div class="content">
                        <div class="product-details-content">
                          <div class="desc-content-box">
                            <p class="text-accent">Canoes are generally less maneuverable than kayaks and SUPs, making them less
                                suitable for navigating through tight spaces or challenging conditions.</p>
                            <p  class="desc-content-box_bottom text-accent">Canoes require working together in tandem with your paddling partner.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
<!-- Huron Canoe -->
      <section v-show="canoe === 'huron'" class="product_detail bottom-fix">
        <div class="container">
          <div class="row">
            <div class="col-xl-6 col-lg-6">
              <div class="product_detail_image">
                <img src="/assets/images/shop/esquifHuron.jpg" alt="">
              </div>
            </div>
            <div class="col-xl-6 col-lg-6">
              <div class="product_detail_content">
                <h2>Huron 16</h2>
                <div class="product_detail_text">
                  <p>“The Huron 16 is ideal for cottagers and recreational canoeists who
                    want a rugged canoe for paddling on calm bodies of water and small rivers but
                    who don’t need the depth and capacity of the Prospecteur 16.”</p>
                </div>
                <ul class="list-unstyled product_detail_address">
                  <li>Weight : 65lbs</li>
                  <li>Capacity : >1000lbs</li>
                  <li>Seats : Webbed seats</li>
                  <li>Length : 4.9 m (16ft)</li>
                  <li>Width : 89 cm (35″)</li>
                  <li>Depth : 31.75 cm (12.5″)</li>
                </ul>
                <h3 class="rental-header">rental Pricing</h3>
                <ul class="list-unstyled product_detail_address">
                  <li><span class="text-base">$35</span> for the first hour and <span class="text-base">$20</span> per additional hour for a maximum of 3 hours</li>
                  <li><span class="text-base">$70</span> 3 hour trip from Rocky Ripple to TPA</li>
                  <li><span class="text-base">$85</span> 4.5 hour trip from IAC to TPA</li>
                </ul>
                <p>One child under 10 years of age and under 100 lbs can ride for free in the canoe.
                    Additional seat rental is $10. No children under the age of 2 years allowed and all
                    children must be able to walk unassisted. Parents must provide their own coast guard
                    approved and unexpired personal floatation device for children under the age of 10.</p>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-xl-12">
              <div class="product-tab-box tabs-box">

                <div class="mission-tabs">

                  <!--Tab-->
                  <input type="radio" name="tabs" id="tab-five" checked="checked">
                  <label for="tab-five" class="tab-btn">Description</label>
                  <div class="tab">
                    <div class="active-tab">
                      <div class="content">

                        <div class="product-details-content">
                          <div class="desc-content-box">
                            <p class="text-accent">The Huron 16 is
                    pulled from the same mold as the Prospecteur 16 but we trim it down to 12.5”, as
                    opposed to 14.5”. The lower profile reduces the weight and makes it easy to
                    paddle in breezy conditions as either a solo or tandem.</p>
                            <p class="desc-content-box_bottom text-acccent">T-Formex is a high tech ABS plastic laminate, specially designed for products that require structural memory and a resistance to abrasion and impacts. These characteristics make it the best choice for canoes. </p>
                          </div>
                        </div>

                      </div>
                    </div>
                  </div>

                  <!--Tab-->
                  <input type="radio" name="tabs" id="tab-six" >
                  <label for="tab-six" class="tab-btn">History of Canoes</label>
                  <div class="tab">
                    <div class="active-tab">
                      <div class="content">

                        <div class="product-details-content">
                          <div class="desc-content-box">
                            <p class="text-accent">Canoes have been used by indigenous peoples in North America for centuries, likely
                                dating back thousands of years. These early canoes were made of bark or dugout logs,
                                and were used for transportation, hunting, and fishing.</p>
                            <p  class="desc-content-box_bottom text-accent">As European colonizers arrived in North America, they brought with them their own
                                canoe designs, which were often made of wood and covered with animal skins or bark.
                                These canoes were used for exploration and trade, as well as for transportation and
                                hunting.</p>
                            <p  class="desc-content-box_bottom text-accent">In the 19th and early 20th centuries, canoes began to be made of more modern
                                materials such as canvas or aluminum. Today, canoes are made from a variety of
                                materials including fiberglass, plastic, and carbon fiber, and are used for a variety of
                                recreational and competitive purposes, including racing, touring, and wilderness
                                expeditions.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!--Tab-->
                  <input type="radio" name="tabs" id="tab-seven" >
                  <label for="tab-seven" class="tab-btn">Benefits of Canoes</label>
                  <div class="tab">
                    <div class="active-tab">
                      <div class="content">
                        <div class="product-details-content">
                          <div class="desc-content-box">
                            <p class="text-accent">Canoes are generally stable and easy to balance in, making them a good choice for
                                beginners or those who are less comfortable on the water.</p>
                            <p  class="desc-content-box_bottom text-accent">Canoes have a large, open design, which makes them suitable for carrying a lot of gear
                                or multiple passengers.</p>
                            <p  class="desc-content-box_bottom text-accent">Canoes are typically slower than kayaks and SUPs, which can be a benefit for leisurely
                                paddling or fishing trips.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <input type="radio" name="tabs" id="tab-eight" >
                  <label for="tab-eight" class="tab-btn">Drawbacks of Canoes</label>
                  <div class="tab">
                    <div class="active-tab">
                      <div class="content">
                        <div class="product-details-content">
                          <div class="desc-content-box">
                            <p class="text-accent">Canoes are generally less maneuverable than kayaks and SUPs, making them less
                                suitable for navigating through tight spaces or challenging conditions.</p>
                            <p  class="desc-content-box_bottom text-accent">Canoes require working together in tandem with your paddling partner.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>


    </div>
</template>

<script>
    export default {
        name: "ProductDetail",
        data() {
          return {
            canoe: 'prospector'
          }
        }
    }
</script>

<style scoped>

  .bottom-fix {
    padding-bottom: 25px;
  }

  tab-one { 
    background-color: var(--thm-accent) !important;
  }
  .header-text {
  color: var(--thm-accent);
  text-shadow: 1px 1px #1a1b1e;
}
  .mission-tabs {
    display: flex;
    flex-wrap: wrap;
  }

  .rental-header {
    padding-top: 25px;
    color: var(--thm-base);
  }
  .text-base {
    color: var(--thm-base);
  }
  .text-accent {
    color: var(--thm-accent) !important;
  }
  .mission-tabs label {
    order: 1;
    display: block;
    padding: 17px 50px;
    margin-right: 0.2rem;
    cursor: pointer;
    background: var(--thm-black);
    font-weight: 500;
    transition: background ease 0.2s;
    font-size: 19px;
    text-transform: uppercase;
    color: var(--thm-accent);
  }
  .mission-tabs .tab {
    order: 99;
    flex-grow: 1;
    width: 100%;
    display: none;
    padding: 1rem;
    background: var(--thm-black);
  }
  .default-tabs .mission-tabs .text {
    position: relative;
    font-size: 20px;
    font-weight: 300;
    color: #5e9054;
    line-height: 1.7em;
    letter-spacing: 2px;
  }
  .mission-tabs input[type="radio"] {
    display: none;
  }
  .mission-tabs input[type="radio"]:checked + label {
    background: var(--thm-base);
    color: var(--thm-accent);
  }
  .mission-tabs input[type="radio"]:checked + label + .tab {
    display: block;
  }

  @media (max-width: 45em) {
    .mission-tabs .tab,
    .mission-tabs label {
      order: initial;
    }
    .mission-tabs label {
      width: 100%;
      margin-right: 0;
      margin-top: 0.2rem;
    }
  }

</style>

