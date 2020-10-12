<template>
  <div id="Home">
    <section class="bannerSec overflow-hidden">
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
<!-- Portfolio -->
    <section class="pt-12 pt-md-15 pt-xl-19">
        <div class="container">
          <div class="row">
            <div class="col-12">
<!-- header -->
              <header class="header text-center mb-8 mb-md-10 mb-xl-14">
                <h2 class="mb-5 mb-md-7">
                  <strong class="h6 font-weight-light mb-3 text-danger text-capitalize d-block fontRoboto">My works</strong>
                  <strong class="text-uppercase d-block">Featured Projects</strong>
                </h2>
                <span class="bdrBtmImg d-block position-relative mx-auto"></span>
              </header>
            </div>
            <div class="col-12">
              <ul class="filterNav filter-button-group list-unstyled fwSemibold fontPoppins text-uppercase mb-5 mb-xl-7 d-flex flex-wrap justify-content-center">
                <li class="nav-item mb-2"><a class="filterBtn is-checked" data-filter="*" href="javascript:void(0);">all</a></li>
                <li class="nav-item mb-2"><a class="filterBtn" data-filter=".project" href="javascript:void(0);">projects</a></li>
                <li class="nav-item mb-2"><a class="filterBtn" data-filter=".paid" href="javascript:void(0);">paid projects</a></li>
                <li class="nav-item mb-2"><a class="filterBtn" data-filter=".entreprenuerial" href="javascript:void(0);">entreprenuerial</a></li>
              </ul>
            </div>
          </div>
        </div>
<!-- gridFilterWrap -->
        <div class="gridFilterWrap d-flex flex-wrap">
<!-- CLS -->
          <div class="element-item itemIV overflow-hidden transition paid" data-category="transition paid">
            <div class="d-block imgHolder w-100">
              <a href="#" data-toggle="modal" data-target="#clsModal"><img src="../../public/images/CLS.jpg" class="img-fluid" alt="image description"></a>
              <div class="overbgBTxt position-absolute">
                <h3>
                  <strong class="fwSemibold px-3 d-inline-block h4 mb-0 d-block"><a href="javascript:void(0);">Concrete Landscape Services</a></strong>
                  <strong class="fontRoboto px-3 d-inline-block designType text-white">Paid Project</strong>
                </h3>
              </div>
            </div>
<!-- CLS Modal -->
            <div class="modal fade" id="clsModal">
              <div class="modal-dialog modal-lg">
                <div class="modal-content">
                  <div class="modal-header">
                    <div class="col span-1-of-2"> 
                      <h1>CLS Services</h1>
                    </div>
                    <div class="col span-1-of-2 date date">
                      <h4>February, 2020</h4>
                    </div>
                  </div>
                  <div class="modal-body">
                    <p>I met a business owner who was in need of rebuilding their website for their landscape company. After revealing to him I am a full stack developer, he hired me for the task. He needed a static website where he could showcase his work. I created a few rough drafts to see what direction he wanted to take the design. It was a valuable experience to take on my first paid project as a developer. The business owner is very happy with the final look and has since referred me to more business owners in his network.</p>
                    <a href="https://www.ConcreteLandscapeServices.com">Concrete Landscape Services</a>
                    <br>
                    <div class="row">
                      <div class="col span-1-of-3">
                        <ul>
                          <li>Vue.js</li>
                          <li>HTML</li>
                          <li>CSS</li>
                          <li>Bootstrap</li>
                          <li>Netlify</li>
                        </ul>
                      </div>
                    </div>
                    <img src="../../public/images/CLSHomeTop.jpg" class=" modal-img">
                  </div>
                  <div class="modal-footer">
                    <button class="btn btn-danger text-uppercase rounded-pill fwSemibold" data-dismiss="modal" value="close">Close</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
<!-- BlockHound -->
          <div class="element-item itemIV overflow-hidden transition project" data-category="transition project">
            <div class="d-block imgHolder w-100">
              <a href="#" data-toggle="modal" data-target="#bhModal"><img src="../../public/images/BHMap.jpg" class="img-fluid" alt="image description"></a>
              <div class="overbgBTxt position-absolute">
                <h3>
                  <strong class="fwSemibold px-3 d-inline-block h4 mb-0 d-block"><a href="javascript:void(0);">BlockHound</a></strong>
                  <strong class="fontRoboto px-3 d-inline-block designType text-white">Project</strong>
                </h3>
              </div>
            </div>
<!-- BlockHound Modal -->
            <div class="modal fade" id="bhModal">
              <div class="modal-dialog modal-lg">
                <div class="modal-content">
                  <div class="modal-header"> 
                    <div class="col span-1-of-2">
                      <h1>BlockHound</h1>
                      <h3>Increasing Dog Safety Through Technology</h3>
                    </div>
                    <div class="col span-1-of-2 date">
                      <h4>February, 2020</h4>
                    </div>
                  </div>
                  <div class="modal-body">
                    <p>Inspired by the neighborhood app NextDoor, I wanted to build an app that helps track your dogs movements. Everyday NextDoor is riddled with posts about losts dogs with vague descriptions and locations. I have created an app that can track your dogs movements, alerts you if your dog escapes, and can notify nearby neighbors with your dogs description and real-time location.</p>
                    <p>For my final project of my coding bootcamp using a culmination of my acquired skill sets, APIs, and GoogleMaps, I created BlockHound. I used Ruby on Rails for the backend, a mixture of HTML, CSS, and Javascript in the Vue.js framework for the front end. I purchased a GPS device from Logistimatics, a North Carolina based company that specializes in tracking devices. By subscribing to their API key, I was able to integrate data obtained from the GPS device I fixed to my dogs collar.</p>
                    <p>Using real time coordinates updated every 30 seconds, I created an alert that would automatically display if my dog ventures beyond my specified boundaries. Once displayed, the user has the option of alerting nearby neighbors, or dismissing the alert. By alerting nearby neighbors, the user is sharing their dogs real time location, description, and owner contact information. The idea is to safely reunite lost dogs to their owners by using technology and some community help.</p>
                    <a target="_blank" href="https://www.youtube.com/watch?v=9quKcQxq630&feature=youtu.be&t=2031" >Watch Demo Here</a>
                  </div>
                    <div class="row">
                      <div class="col span-1-of-2">
                        <ul>
                          <li>Ruby on Rails</li>
                          <li>Vue.js</li>
                          <li>Javascript</li>
                          <li>HTML</li>
                          <li>CSS</li>
                          <li>APIs</li>
                          <li>Bootstrap</li>
                        </ul>
                      </div>
                      <div class="col span-1-of-2">
                        <img src="../../public/images/blockhound.jpg" class="img-fluid modal-img">
                      </div>
                    </div>
                  <div class="modal-footer">
                    <button class="btn btn-danger text-uppercase rounded-pill fwSemibold" data-dismiss="modal" value="close">Close</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
<!-- Christoffersen Collection -->
          <div class="element-item itemIV overflow-hidden transition paid" data-category="transition paid">
            <div class="d-block imgHolder w-100">
              <a href="../../public/images/CC.jpg" data-fancybox="gallery" data-caption="Mockup Can Design"><img src="../../public/images/CC.jpg" class="img-fluid" alt="image description"></a>
              <div class="overbgBTxt position-absolute">
                <h3>
                  <strong class="fwSemibold px-3 d-inline-block h4 mb-0 d-block"><a href="javascript:void(0);">Christoffersen Collection</a></strong>
                  <strong class="fontRoboto px-3 d-inline-block designType text-white">Paid Project</strong>
                </h3>
              </div>
            </div>
          </div>
  <!-- Corsega Eyewear -->
          <div class="element-item itemIV overflow-hidden transition entreprenuerial" data-category="transition entreprenuerial">
            <div class="d-block imgHolder w-100">
              <a href="#" data-toggle="modal" data-target="#corsegaModal"><img src="../../public/images/Blue2.jpg" class="img-fluid" alt="image description"></a>
              <div class="overbgBTxt position-absolute">
                <h3>
                  <strong class="fwSemibold px-3 d-inline-block h4 mb-0 d-block"><a href="javascript:void(0);">Corsega Eyewear</a></strong>
                  <strong class="fontRoboto px-3 d-inline-block designType text-white">Entrepreneurial Project</strong>
                </h3>
              </div>
            </div>
            <div class="modal fade" id="corsegaModal">
              <div class="modal-dialog modal-lg">
                <div class="modal-content">
                  <div class="modal-header"> 
                    <h1>Corsega Eyewear</h1>
                    <h3>#CorsegaEyewear</h3>
                    <h4>July, 2013 - December, 2016</h4>
                  </div>
                  <div class="modal-body">
                    <p>Following my entrepreneurial spirit, I wanted to build a company. I would constantly break or lose expensive sunglasses. I believed stylish, quality sunglasses with polarized lenses should be affordable. So in 2014, after a year of research and development, I launched my own sunglasses company: Corsega Eyewear.</p>
                    <p>The idea came to me right after I overpaid for a pair of sunglasses during a trip to Barcelona, Spain in the summer of 2013. I analyzed the glasses on the balcony of my hostel and became really intrigued about what the net cost of producing sunglasses were. After learning the cost and profit margins that are typically associated with the eyewear industry, I decided to start my own company. After a year of research and development, Corsega Eyewear was born July, 2014.</p>
                    <p>Once the online store became live, I marketed my sunglasses through social media and paid advertising. I took direct lessons from my Digital Marketing classes and applied them to my real time business project. I soon found strategies and techniques that were much more efficient than others, such as Search Engine Optimization (SEO) vs. Search Engine Marketing (SEM). My sunglasses were also being sold in boutiques throughout the San Francisco and Petaluma area. I reached profitability within 11 months and ran the company for another two years before shutting it down and relocating to the Sacramento area.</p>
                    <a href="https://www.ConcreteLandscapeServices.com">Concrete Landscape Services</a>
                    <br>
                    <div class="row">
                      <div class="col span-1-of-3">
                        <ul>
                          <li>Vue.js</li>
                          <li>HTML</li>
                          <li>CSS</li>
                          <li>Bootstrap</li>
                          <li>Netlify</li>
                        </ul>
                      </div>
                    </div>
                    <img src="../../public/images/CLSHomeTop.jpg" class=" modal-img">
                  </div>
                  <div class="modal-footer">
                    <button class="btn btn-danger text-uppercase rounded-pill fwSemibold" data-dismiss="modal" value="close">Close</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
<!-- 4x4 Teardrops -->
          <div class="element-item itemIV overflow-hidden transition paid" data-category="transition paid">
            <div class="d-block imgHolder w-100">
              <a href="../../public/images/XTR1.jpg" data-fancybox="gallery" data-caption="Mockup Can Design"><img src="../../public/images/XTR1.jpg" class="img-fluid" alt="image description"></a>
              <div class="overbgBTxt position-absolute">
                <h3>
                  <strong class="fwSemibold px-3 d-inline-block h4 d-block mb-0"><a href="javascript:void(0);">4X4 Teardrops</a></strong>
                  <strong class="fontRoboto px-3 d-inline-block designType text-white">Paid Project</strong>
                </h3>
              </div>
            </div>
          </div>
          <!-- element-item -->
          <div class="element-item itemIV overflow-hidden transition overlay design" data-category="transition design">
            <div class="d-block imgHolder w-100">
              <img src="images/img14.jpg" class="img-fluid" alt="image description">
              <div class="overTxt position-absolute">
                <h3>
                  <strong class="fwSemibold d-block h4 d-block mb-2"><a href="images/img14.jpg" data-fancybox="gallery" data-caption="Mockup Can Design">Mockup Can Design</a></strong>
                  <strong class="fontRoboto d-block designType text-white">Design - Branding</strong>
                </h3>
              </div>
            </div>
          </div>
          <!-- element-item -->
          <div class="element-item itemIV overflow-hidden transition photo" data-category="transition photo">
            <div class="d-block imgHolder w-100">
              <a href="images/img15.jpg" data-fancybox="gallery" data-caption="Mockup Can Design"><img src="images/img15.jpg" class="img-fluid" alt="image description"></a>
              <div class="overbgBTxt position-absolute">
                <h3>
                  <strong class="fwSemibold px-3 d-inline-block h4 d-block mb-0"><a href="javascript:void(0);">Mockup Can Design</a></strong>
                  <strong class="fontRoboto px-3 d-inline-block designType"> text-whiteDesign - Branding</strong>
                </h3>
              </div>
            </div>
          </div>
          <!-- element-item -->
          <div class="element-item itemIV overflow-hidden overlay app web" data-category="app web">
            <div class="d-block imgHolder w-100">
              <img src="images/img16.jpg" class="img-fluid" alt="image description">
              <div class="overTxt position-absolute">
                <h3>
                  <strong class="fwSemibold d-block h4 d-block mb-2"><a href="images/img16.jpg" data-fancybox="gallery" data-caption="Mockup Can Design">Mockup Can Design</a></strong>
                  <strong class="fontRoboto d-block designType text-white">Design - Branding</strong>
                </h3>
              </div>
            </div>
          </div>
        </div>
      </section>

  </div>

</template>

<script>

// export default {
//   modal:('#myModal').on('shown.bs.modal', function() {('#myInput').trigger('focus');})
// };
</script>
