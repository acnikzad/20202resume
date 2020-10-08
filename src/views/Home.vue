<template>
  <section id="Home" class="bannerSec overflow-hidden">
  <!-- bannerSlide -->
    <div class="bannerSlide d-block header1">
      <!-- bannerWrap -->
      <div class="bannerWrap overlay d-flex position-relative overflow-hidden">
        <div class="alignCenter w-100 d-flex align-items-center">
          <div class="container pt-25 pb-14 pt-sm-33 pb-sm-20">
            <div class="caption position-relative text-center text-white">
              <h1 class="h1 text-uppercase text-white mb-4">
                <div class="row hero-margin">
                  <img src="../../public/images/2020headshotsidesquare.jpg" class="hero-pic">
                  <div class="col">
                    <h1 class="d-block font-weight-light mb-n1 mb-sm-2 hero-text">Aria Nikzad</h1>
                    <h2 class="d-block font-weight-light hero-text">Full Stack Developer</h2>
                    <div class="icon-small">
                      <i class="devicon-ruby-plain"></i>
                      <i class="devicon-rails-plain"></i>
                      <i class="devicon-vuejs-plain"></i>
                      <i class="devicon-javascript-plain"></i>
                      <i class="devicon-css3-plain"></i>
                      <i class="devicon-html5-plain"></i>
                      <i class="devicon-bootstrap-plain"></i>
                      <i class="devicon-github-plain"></i>
                      <i class="ion-social-bitcoin"></i>
                    </div>
                  </div>
                </div>
              </h1>
              <a href="javascript:void(0);" class="btn btn-danger text-uppercase rounded-pill fwSemibold">learn more</a>
            </div>
          </div>
        </div>
        <span class="bgImg bgCover position-absolute" style="background-image: url(images/img45.jpg)"></span>
      </div>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
