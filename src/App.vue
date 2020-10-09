<template>
  <div id="app">
    <header id="pageHeader" class="position-absolute">
      <div class="d-flex align-items-center mx-3 mx-md-6 py-3 py-lg-0">
        <!-- mainLogo -->
        <div class="logo mt-n1">
          <a href="homepage.html">
            <h3>Aria Nikzad</h3>
          </a>
        </div>
        <!-- menuHolder -->
        <div class="d-flex menuHolder justify-content-end align-items-center flex-grow-1">
          <!-- navbar -->
          <nav class="navbar navbar-expand-lg navHolder fwSemibold navbar-light p-0 mr-3 mr-lg-6 mr-xl-7 fontPoppins position-static">
            <button class="navbar-toggler navOpener" type="button" data-toggle="collapse" data-target="#navBarOpener" aria-controls="navBarOpener" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse navCollapse mainNav" id="navBarOpener">
              <!-- navbar-nav -->
              <ul class="navbar-nav mr-auto text-uppercase">
                <li class="nav-item">
                  <a class="nav-link plr-8" href="#Home">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link plr-8" href="#Portfolio">Portfolio</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link plr-8" href="#About">About Me</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link plr-8" href="#Contact">Contact</a>
                </li>
              </ul>
            </div>
          </nav>
<!-- menuSocialNetworks -->
          <ul class="list-unstyled mb-0 d-flex menuSocialNetworks pl-xl-4">
          
            <li class="d-none d-lg-inline-block position-relative">
              <a href="javascript:void(0);" class="sideOpener"><i class="fas fa-bars"></i></a>
              <!-- sideNavBar -->
              <div class="sideNavBar position-fixed">
                <!-- sideNav -->
                <div class="sideNav px-10 pt-20 pb-6">
                  <a href="javascript:void(0);" class="sideClose position-absolute mb-3"><i class="fa fa-times"></i></a>
                  <h2 class="sideLogo mb-7 fontPoppins fwSemibold text-white text-uppercase"><a href="javascript:void(0);">Kyata</a></h2>
                  <p class="mb-9">We tackle business problems with intelligence. We use cutting-edge tech and cutting-edge thinking to bring brands to life online and direct consumer behavior.</p>
                  <span class="hr d-block mb-10"></span>
                  <h6 class="h6 fwSemibold text-white text-uppercase mb-5 mb-lg-7">Our Services</h6>
                  <ul class="list-unstyled mb-10 fNav fontRoboto">
                    <li><a class="position-relative pl-3" href="javascript:void(0);">Interface Design</a></li>
                    <li><a class="position-relative pl-3" href="javascript:void(0);">User Experience</a></li>
                    <li><a class="position-relative pl-3" href="javascript:void(0);">Mobile Application</a></li>
                    <li><a class="position-relative pl-3" href="javascript:void(0);">Web Development</a></li>
                    <li><a class="position-relative pl-3" href="javascript:void(0);">Wireframes Design</a></li>
                    <li><a class="position-relative pl-3" href="javascript:void(0);">Branding &amp; Identity</a></li>
                  </ul>
                  <span class="hr d-block mb-9"></span>
                  <h6 class="h6 fwSemibold text-center text-sm-left text-white text-uppercase mb-5 mb-lg-7"> Instagram Widget</h6>
                  <ul class="list-unstyled instImgWrap mb-4 d-flex flex-wrap">
                    <li>
                      <a href="images/img09.jpg" data-fancybox="gallery" class="position-relative d-block">
                        <img src="images/img09.jpg" class="img-fluid" alt="image description">
                      </a>
                    </li>
                    <li>
                      <a href="images/img10.jpg" data-fancybox="gallery" class="position-relative d-block">
                        <img src="images/img10.jpg" class="img-fluid" alt="image description">
                      </a>
                    </li>
                    <li>
                      <a href="images/img11.jpg" data-fancybox="gallery" class="position-relative d-block">
                        <img src="images/img11.jpg" class="img-fluid" alt="image description">
                      </a>
                    </li>
                    <li>
                      <a href="images/img12.jpg" data-fancybox="gallery" class="position-relative d-block">
                        <img src="images/img12.jpg" class="img-fluid" alt="image description">
                      </a>
                    </li>
                    <li>
                      <a href="images/img13.jpg" data-fancybox="gallery" class="position-relative d-block">
                        <img src="images/img13.jpg" class="img-fluid" alt="image description">
                      </a>
                    </li>
                    <li>
                      <a href="images/img14.jpg" data-fancybox="gallery" class="position-relative d-block">
                        <img src="images/img14.jpg" class="img-fluid" alt="image description">
                      </a>
                    </li>
                    <li>
                      <a href="images/img15.jpg" data-fancybox="gallery" class="position-relative d-block">
                        <img src="images/img15.jpg" class="img-fluid" alt="image description">
                      </a>
                    </li>
                    <li>
                      <a href="images/img16.jpg" data-fancybox="gallery" class="position-relative d-block">
                        <img src="images/img16.jpg" class="img-fluid" alt="image description">
                      </a>
                    </li>
                  </ul>
                  <span class="instTxt fontRoboto font-weight-normal d-block mb-16"><a href="javascript:void(0);"><i class="fab fa-instagram mr-xl-1"></i> Follow us in Instagram</a></span>
                  <span class="ftTxt d-block">2019 © <a href="javascript:void(0);">Kyata Template.</a> All rights reserved.</span>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <span class="sideOver"></span>
    </header>
    <router-view/>
<!-- footerArea -->
    <footer class="footerArea py-5 py-md-6">
      <div class="container">
        <div class="row align-items-center">
    <!--       <div class="row"> -->
            <div class="col span-1-of-3">
              <span class="ftTxt d-block">Aria Nikzad</span>
              <span class="ftTxt d-block">Sacramento, CA</span>
              <span class="ftTxt d-block">(415) 328-7478</span>
            </div>
            <div class="col span-1-of-3">
              <span class="ftTxt d-block text-center">"The same boiling water that softens the potato hardens the egg. It's about what you're made of, not the circumstances." - Mel Robbins</span>
            </div>
            <div class="col span-1-of-3">
              <ul class="list-unstyled ftSocialNetworks d-flex justify-content-center justify-content-sm-end mb-2 mb-sm-0">
                <li><a href="javascript:void(0);" class="fab fa-linkedin"></a></li>
                <li><a href="javascript:void(0);" class="fab fa-instagram"></a></li>
              </ul>
            </div>
          <!-- </div> -->
        </div>
      </div>
    </footer>
  </div>
</template>

<style>

</style>
