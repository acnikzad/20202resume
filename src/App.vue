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
                  <a class="nav-link plr-8" href="#About">About Me</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link plr-8" href="#portfolio">Portfolio</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link plr-8" href="#footer">Contact</a>
                </li>
              </ul>
            </div>
          </nav>
        </div>
      </div>
      <span class="sideOver"></span>
    </header>
    <router-view/>
<!-- footerArea -->
    <footer class="footerHolder pt-11 pb-lg-4" id="footer">
      <div class="container">
        <div class="row align-items-center">
          <div class="col span-1-of-3">
            <address class="d-block">
              <ul class="list-unstyled ftContctHolder mb-0 text-center text-md-left">
                <li>Located: <span class="text-white">Sacramento, Ca</span></li>
                <li>Email: <a href="javascript:void(0);" type="Email">a.c.nikzad@gmail.com</a></li>
                <li>Phone: <a href="tel:4153287478">415 328-7478</a></li>
              </ul>
            </address>
          </div>
          <div class="col span-1-of-3">
            <span class="ftTxt d-block text-center">"The same boiling water that softens the potato hardens the egg. It's about what you're made of, not the circumstances." - Mel Robbins</span>
          </div>
          <div class="col span-1-of-3">
            <ul class="list-unstyled ftSocialNetworks d-flex justify-content-center justify-content-lg-end mb-2 mb-sm-0">
              <li><a href="https://www.linkedin.com/in/arianikzad/" target="_blank" class="fab fa-linkedin"></a></li>
              <li><a href="https://www.instagram.com/acnikzad/?hl=en" target="_blank" class="fab fa-instagram"></a></li>
              <li><a href="https://github.com/acnikzad" target="_blank" class="fab fa-github"></a></li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>

</style>
