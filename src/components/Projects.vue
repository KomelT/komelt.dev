<script setup lang="ts">
import BigTitle from './BigTitle.vue';
</script>

<template>
  <div class="page" id="projects">
    <!-- Main Content Starts -->
    <div class="portfolio">
      <BigTitle title="my portfolio" subtitle="works" />
      <div class="main-content text-center">
        <div id="grid-gallery" class="container grid-gallery">
          <!-- Portfolio Grid Starts -->
          <div class="grid-wrap">
            <ul class="row grid gridlist">
              <!-- Portfolio Item Starts -->
              <li>
                <figure>
                  <img src="../assets/img/projects/jaz_in_ti.jpg" alt="Portolio Image">
                  <div>
                    <span>Image Project</span>
                  </div>
                </figure>
              </li>
              <!-- Portfolio Item Ends -->
            </ul>
          </div>
          <!-- Portfolio Grid Ends -->
          <!-- Portfolio Details Starts -->
          <div class="slideshow">
            <ul>
              <!-- Portfolio Item Detail Starts -->
              <li>
                <figure>
                  <!-- Project Details Starts -->
                  <figcaption>
                    <h3>Image Project</h3>
                    <div class="row open-sans-font">
                      <div class="col-12 col-sm-6 mb-2">
                        <i class="fa fa-file-text-o pr-2"></i>
                        <span class="project-label">Project </span>: <span class="ft-wt-600 uppercase">Website</span>
                      </div>
                      <div class="col-12 col-sm-6 mb-2">
                        <i class="fa fa-user-o pr-2"></i>
                        <span class="project-label">Client </span>: <span class="ft-wt-600 uppercase">Envato</span>
                      </div>
                      <div class="col-12 col-sm-6 mb-2">
                        <i class="fa fa-code pr-2"></i>
                        <span class="project-label">Langages </span>: <span class="ft-wt-600 uppercase">HTML, CSS,
                          Javascript</span>
                      </div>
                      <div class="col-12 col-sm-6 mb-2">
                        <i class="fa fa-external-link pr-2"></i>
                        <span class="project-label">Preview </span>: <span class="ft-wt-600 uppercase">
                          <a href="#" target="_blank">www.envato.com</a>
                        </span>
                      </div>
                    </div>
                  </figcaption>
                  <!-- Project Details Ends -->
                  <!-- Main Project Content Starts -->
                  <img src="../assets/img/projects/jaz_in_ti.jpg" alt="Portolio Image">
                  <!-- Main Project Content Ends -->
                </figure>
              </li>
            </ul>
            <!-- Portfolio Navigation Starts -->
            <nav>
              <span class="icon nav-prev">
                <img src="../assets/icons/left-arrow.png" alt="previous">
              </span>
              <span class="icon nav-next">
                <img src="../assets/icons/right-arrow.png" alt="next">
              </span>
              <span class="nav-close">
                <img src="../assets/icons/close-button.png" alt="close">
              </span>
            </nav>
            <!-- Portfolio Navigation Ends -->
          </div>
        </div>
      </div>
    </div>
    <!-- Main Content Ends -->
  </div>
</template>
<style scoped>
/*** Portfolio ***/
.portfolio .main-content {
  padding-bottom: 60px;
  margin-top: -15px;
}

/* Grid */

.portfolio .grid-gallery ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.portfolio .grid-gallery figure {
  margin: 0;
}

.portfolio .grid-gallery figure img {
  display: block;
  width: 100%;
  border-radius: 5px;
  transition: .3s;
}

.portfolio .grid-wrap {
  margin: 0 auto;
}

.portfolio .grid {
  margin: 0 auto;
}

.portfolio .grid li {
  width: 33.333333%;
  float: left;
  cursor: pointer;
  padding: 15px;
}

.portfolio .grid figure {
  -webkit-transition: 0.3s;
  transition: 0.3s;
  border-radius: 5px;
  padding: 0;
  position: relative;
  overflow: hidden;
}

.portfolio .grid figure img {
  display: block;
  position: relative;
}

.portfolio .grid li a {
  overflow: hidden;
}

.portfolio .grid li figure div {
  position: absolute;
  width: 100%;
  height: 100%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  text-align: center;
  justify-content: center;
}

.portfolio .grid li figure div span {
  margin: 0;
  text-transform: uppercase;
  color: #fff;
  font-size: 18px;
}

/* Slideshow */

.portfolio .slideshow {
  position: fixed;
  background: rgba(0, 0, 0, 0.85);
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  z-index: 1111;
  opacity: 0;
  visibility: hidden;
  overflow: hidden;
  -webkit-perspective: 1000px;
  perspective: 1000px;
  -webkit-transition: opacity 0.5s, visibility 0s 0.5s;
  transition: opacity 0.5s, visibility 0s 0.5s;
  text-align: left;
}

.portfolio .slideshow-open .slideshow {
  opacity: 1;
  visibility: visible;
  -webkit-transition: opacity 0.5s;
  transition: opacity 0.5s;
}

.portfolio .slideshow ul {
  width: 100%;
  height: 100%;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  -webkit-transform: translate3d(0, 0, 150px);
  transform: translate3d(0, 0, 150px);
  -webkit-transition: -webkit-transform 0.5s;
  transition: transform 0.5s;
}

.portfolio .slideshow ul.animatable>li {
  -webkit-transition: -webkit-transform 0.5s;
  transition: transform 0.5s;
}

.portfolio .slideshow-open .slideshow ul {
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}

.portfolio .slideshow ul>li {
  width: 660px;
  position: absolute;
  top: 50%;
  left: 50%;
  margin: -280px 0 0 -330px;
  visibility: hidden;
}

.portfolio .slideshow ul>li.show {
  visibility: visible;
}

.portfolio .slideshow ul>li:after {
  content: '';
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background: rgba(0, 0, 0, 0.7);
  -webkit-transition: opacity 0.3s;
  transition: opacity 0.3s;
  z-index: 111;
  border-radius: 10px;
}

.portfolio .slideshow ul>li.current:after {
  visibility: hidden;
  opacity: 0;
  -webkit-transition: opacity 0.3s, visibility 0s 0.3s;
  transition: opacity 0.3s, visibility 0s 0.3s;
}

.portfolio .slideshow figure {
  width: 100%;
  height: 100%;
  background: #252525;
  padding: 30px;
  overflow: auto;
  border-radius: 10px;
}

.portfolio .slideshow a {
  text-decoration: underline;
}

.portfolio .slideshow figcaption {
  margin-bottom: 15px;
}

.portfolio .slideshow figcaption h3 {
  text-transform: uppercase;
  padding: 10px 0 20px;
  font-weight: 700;
  text-align: center;
  font-size: 33px;
}

/* Embedded Videos */

.portfolio .slideshow .videocontainer,
.portfolio .slideshow .responsive-video {
  max-width: 100%;
  border-radius: 4px;
  display: block;
  object-fit: cover;
}

.portfolio .slideshow .videocontainer {
  position: relative;
  padding-bottom: 56.20%;
  padding-top: 0;
  height: 0;
  max-width: 100%;
  overflow: hidden;
  width: 100%;
  display: block;
  margin: 0;
  border-radius: 4px;
}

.portfolio .slideshow .videocontainer iframe,
.portfolio .slideshow .videocontainer object,
.portfolio .slideshow .videocontainer embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}

/* Carousel */

.portfolio .slideshow .carousel-indicators {
  bottom: 0;
  background: rgba(0, 0, 0, .4);
  padding: 10px 0;
  margin: 0;
}

.portfolio .slideshow .carousel-indicators li {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  margin: 0 7px;
  background-color: #fff;
  opacity: 1;
}

/* Navigation */

.portfolio .slideshow nav span {
  position: fixed;
  z-index: 1000;
  text-align: center;
  cursor: pointer;
  padding: 200px 30px;
  color: #fff;
}

.portfolio .slideshow nav span.nav-prev,
.portfolio .slideshow nav span.nav-next {
  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
  font-size: 41px;
  line-height: 58px;
}

.portfolio .slideshow nav span.nav-prev {
  left: 0;
}

.portfolio .slideshow nav span.nav-next {
  right: 0;
}

.portfolio .slideshow nav span.nav-close {
  top: 30px;
  right: 30px;
  padding: 0;
}
</style>