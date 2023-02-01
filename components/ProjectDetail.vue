<template>
  <section class="project_detail">
    <div class="container">
      <div class="row">
        <div class="col-xl-12 col-lg-12 col-md-12">
          <div class="project_detail_image">
            <img src="/assets/images/project/project-detail-img-1.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-8 col-lg-7">
          <div class="project_detail_left_content">
            <div class="harvest_innovations_detail">
              <h2>About Our Partner</h2>
              <p class="text-accent">Since its creation in 1991, The Parks Alliance has been committed to changing expectations for Indianapolis’ parks by focusing resources in strategic areas that strengthen our community and elevate parks and trails and eliminate food insecurity.</p>

              <p class="harvest_innovations_detail_bottom_text text-accent">For more than 20 years, The Parks Alliance has been proud to partner with the City of Indianapolis and the Central Indiana Community Foundation (CICF) to lead the development and maintenance of Indy’s parks, trails, greenways, and public spaces. Having received over $17M in grants from the Lilly Endowment, we have made significant infrastructure improvements in the city’s most urban and utilized parks.</p>
            </div>
            <div class="project_detail_last_text">
              <p class="text-accent">And building on the successes over the years, we are focusing our funds on truly transformative projects, including Tarkington Park, Riverside Park, Indy Urban Acres, and Frederick Douglass Park. In the coming years, The Park Alliance of Indianapolis will continue to aid the City through its fundraising and advocacy efforts of additional transformative public spaces.</p>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-5">
          <div class="project_information_box">
            <h3>information</h3>
            <ul class="project_information_list list-unstyled">
              <li><span>Created:</span>1991</li>
              <li><span>Website:</span><a class="web-link" href="https://www.parks-alliance.org" target="_blank">parks-alliance.org</a></li>
              <li><span>Location:</span> 3001 N White River Parkway W. Drive, Indianapolis, IN 46222</li>
            </ul>
            <div class="project_information__social">
              <a href="#"><i class="fab fa-facebook-square"></i></a>
              <a href="#"><i class="fab fa-twitter"></i></a>
              <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ProjectDetail"
    }
</script>

<style scoped>
.text-accent {
  color: var(--thm-accent);
}
.web-link {
  color: var(--thm-black);
}
</style>
