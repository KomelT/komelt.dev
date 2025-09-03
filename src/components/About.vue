<template>
  <!-- Page Title Starts -->
  <section id="about"
    class="title-section text-left text-sm-center revealator-slideup revealator-once revealator-delay1 poppins-font">
    <h1>ABOUT <span>ME</span></h1>
    <span class="title-bg">Resume</span>
  </section>
  <!-- Page Title Ends -->

  <!-- Main Content Starts -->
  <section class="main-content revealator-slideup revealator-once revealator-delay1">
    <div class="container">
      <div class="row">

        <!-- Personal Info Starts -->
        <div class="col-12 col-lg-5 col-xl-6 mg-0-a">
          <div class="row">
            <div class="col-12">
              <h3 class="poppins-font text-uppercase text-sm-center custom-title mb-3 ft-wt-600">personal infos</h3>
            </div>
            <div class="col-12 d-block d-sm-none">
              <img src="../assets/tilen_komel500x500.jpg" class="img-fluid main-img-mobile" alt="my picture" />
            </div>
            <div class="col-6">
              <ul class="about-list list-unstyled open-sans-font">
                <li>
                  <span class="title">first name: </span>
                  <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">Tilen</span>
                </li>
                <li>
                  <span class="title">last name: </span>
                  <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">Komel</span>
                </li>
                <li>
                  <span class="title">Age: </span>
                  <span id="age" class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">{{ new
                    Date().getFullYear() - 2002 }}
                    Years</span>
                </li>
                <li>
                  <span class="title">Country: </span>
                  <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">Slovenia</span>
                </li>
                <li>
                  <span class="title">GitHub:</span>
                  <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block"><a
                      href="https://github.com/KomelT" target="_blank">@KomelT</a></span>
                </li>
              </ul>
            </div>
            <div class="col-6">
              <ul class="about-list list-unstyled open-sans-font">
                <li>
                  <span class="title">Mastodon: </span>
                  <span
                    class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">@komelt(at)toot(dot)tux.si</span>
                </li>
                <li>
                  <span class="title">Email: </span>
                  <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">me(at)komelt(dev)dev</span>
                </li>
                <li>
                  <span class="title">Discord: </span>
                  <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">KomelT</span>
                </li>
                <li>
                  <span class="title">langages: </span>
                  <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">Slovenian,
                    English</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <!-- Personal Info Ends -->
      </div>

      <hr class="separator mt-4" />

      <!-- Experience & Education Starts -->
      <div class="row">
        <div class="col-12">
          <h3 class="text-uppercase pb-5 mb-0 text-left text-sm-center custom-title ft-wt-600">
            Experience <span>&</span> Education
          </h3>
        </div>

        <div class="col-lg-6 m-15px-tb">
          <div class="resume-box">
            <ul>
              <li>
                <div class="icon">
                  <i class="fa fa-graduation-cap"></i>
                </div>
                <span class="time open-sans-font text-uppercase">2025</span>
                <h5 class="poppins-font text-uppercase">
                  internship <span class="place open-sans-font">Codeventuri d.o.o.</span>
                </h5>
                <p class="open-sans-font">
                  I had 5 month internship at <strong>Codeventuri d.o.o.</strong> where I was
                  working on back-end and front-end. With Django and Next.js. I also configured Geoserver and
                  displayed the data on a web map.
                </p>
              </li>
              <li>
                <div class="icon">
                  <i class="fa fa-briefcase"></i>
                </div>
                <span class="time open-sans-font text-uppercase">2021 - PRESENT</span>
                <h5 class="poppins-font text-uppercase">
                  Started studying CS<span class="place open-sans-font">schooling</span>
                </h5>
                <p class="open-sans-font" style="margin:0.5em 0;"><strong>University:</strong> University of
                  Ljubljana,
                  Faculty of Computer and Information Science</p>
                <p class="open-sans-font">
                  <strong>Educationa program:</strong> Computer and information science
                </p>
              </li>
              <li>
                <div class="icon">
                  <i class="fa fa-briefcase"></i>
                </div>
                <span class="time open-sans-font text-uppercase">2017 - 2021</span>
                <h5 class="poppins-font text-uppercase">
                  Graduated from high school<span class="place open-sans-font">schooling</span>
                </h5>
                <p class="open-sans-font">
                  Graduated as gold high school graduate from vocational matura.</p>
                <p class="open-sans-font" style="margin:0.5em 0;"><strong>School:</strong> School
                  centre Nova Gorica, Electrical engineering and computer science school</p>
                <p class="open-sans-font">
                  <strong>Educationa program:</strong> Computer technician
                </p>
              </li>
            </ul>
          </div>
        </div>

        <div class="col-lg-6 m-15px-tb">
          <div class="resume-box">
            <ul>
              <li>
                <div class="icon">
                  <i class="fa fa-briefcase"></i>
                </div>
                <span class="time open-sans-font text-uppercase">2020 - present</span>
                <h5 class="poppins-font text-uppercase">
                  Homelab <span class="place open-sans-font">servers</span>
                </h5>
                <p class="open-sans-font">To expand my knowledge about servers, Linux server and
                  hosting, I bought my first server <strong>HP Proliant DL380</strong>.</p>
              </li>
              <li>
                <div class="icon">
                  <i class="fa fa-graduation-cap"></i>
                </div>
                <span class="time open-sans-font text-uppercase">2020 - present</span>
                <h5 class="poppins-font text-uppercase">
                  Student work<span class="place open-sans-font">Topis Mojca Babuder s.p.</span>
                </h5>
                <p class="open-sans-font">Often working on projects with <a href="https://www.ad4u.eu"
                    target="_blank"><strong>Topis Mojca Babuder s.p.</strong></a>, I am working with
                  Wordpress sites and servers.</p>
              </li>
              <li>
                <div class="icon">
                  <i class="fa fa-graduation-cap"></i>
                </div>
                <span class="time open-sans-font text-uppercase">2018 and 2019</span>
                <h5 class="poppins-font text-uppercase">
                  internship <span class="place open-sans-font">Gostol-Gopan d.o.o.</span>
                </h5>
                <p class="open-sans-font">
                  I had two week internship at <strong>Gostol-Gopan d.o.o.</strong> where I was
                  working with
                  networking equipment.
                </p>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <!-- Experience & Education Ends -->

    </div>
  </section>
</template>
<style scoped>
.main-content {
  padding-bottom: 20px;
}

/* Personal Info List */

.about-list li:not(:last-child) {
  padding-bottom: 20px;
}

.about-list .title {
  opacity: 0.8;
  text-transform: capitalize;
}

.about-list .value {
  font-weight: 600;
}

/* Box Stats */

.box-stats {
  padding: 20px 30px 25px 40px;
  border-radius: 5px;
  border: 1px solid #252525;
}

.box-stats.with-margin {
  margin-bottom: 30px;
}

.box-stats h3 {
  position: relative;
  display: inline-block;
  margin: 0;
  font-size: 50px;
  font-weight: 700;
}

.box-stats h3:after {
  content: '+';
  position: absolute;
  right: -24px;
  font-size: 33px;
  font-weight: 300;
  top: 2px;
}

.box-stats p {
  padding-left: 45px;
}

.box-stats p:before {
  content: '';
  position: absolute;
  left: 0;
  top: 13px;
  width: 30px;
  height: 1px;
  background: #777;
}

/* Resume */

.resume-box ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

.resume-box li {
  position: relative;
  padding: 0 20px 0 60px;
  margin: 0 0 50px;
}

.resume-box li:after {
  content: '';
  position: absolute;
  top: 0;
  left: 20px;
  bottom: 0;
  border-left: 1px solid #333;
}

.resume-box .icon {
  width: 40px;
  height: 40px;
  position: absolute;
  left: 0;
  right: 0;
  line-height: 40px;
  text-align: center;
  z-index: 1;
  border-radius: 50%;
  color: #fff;
  background-color: #252525;
}

.resume-box .time {
  color: #fff;
  font-size: 12px;
  padding: 1px 10px;
  display: inline-block;
  margin-bottom: 12px;
  border-radius: 20px;
  font-weight: 600;
  background-color: #252525;
  opacity: 0.8;
}

.resume-box h5 {
  font-size: 18px;
  margin: 7px 0 10px;
}

.resume-box p {
  margin: 0;
  color: #eee;
  font-size: 14px;
}

.resume-box .place {
  opacity: 0.8;
  font-weight: 600;
  font-size: 15px;
  position: relative;
  padding-left: 26px;
}

.resume-box .place:before {
  position: absolute;
  content: '';
  width: 10px;
  height: 2px;
  background-color: #fff;
  left: 7px;
  top: 9px;
  opacity: 0.8;
}

@media (max-width: 1350px) and (min-width: 992px) {
  .container {
    max-width: calc(100% - 195px);
  }
}


.c100 .bar {
  position: absolute;
  border: 0.08em solid #307bbb;
  width: 0.84em;
  height: 0.84em;
  clip: rect(0em, 0.5em, 1em, 0em);
  border-radius: 50%;
  -webkit-transform: rotate(0deg);
  -moz-transform: rotate(0deg);
  -ms-transform: rotate(0deg);
  -o-transform: rotate(0deg);
  transform: rotate(0deg);
}

.c100 {
  position: relative;
  font-size: 120px;
  width: 1em;
  height: 1em;
  border-radius: 50%;
  float: left;
  margin: 0 0.1em 0.1em 0;
  background-color: #cccccc;
}

.c100 *,
.c100 *:before,
.c100 *:after {
  -webkit-box-sizing: content-box;
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.c100.center {
  float: none;
  margin: 0 auto;
}

.c100>span {
  position: absolute;
  width: 100%;
  z-index: 1;
  left: 0;
  top: 0;
  width: 5em;
  line-height: 5em;
  font-size: 0.2em;
  color: #cccccc;
  display: block;
  text-align: center;
  white-space: nowrap;
  -webkit-transition-property: all;
  -moz-transition-property: all;
  -o-transition-property: all;
  transition-property: all;
  -webkit-transition-duration: 0.2s;
  -moz-transition-duration: 0.2s;
  -o-transition-duration: 0.2s;
  transition-duration: 0.2s;
  -webkit-transition-timing-function: ease-out;
  -moz-transition-timing-function: ease-out;
  -o-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
}

.c100:after {
  position: absolute;
  top: 0.08em;
  left: 0.08em;
  display: block;
  content: " ";
  border-radius: 50%;
  background-color: #f5f5f5;
  width: 0.84em;
  height: 0.84em;
  -webkit-transition-property: all;
  -moz-transition-property: all;
  -o-transition-property: all;
  transition-property: all;
  -webkit-transition-duration: 0.2s;
  -moz-transition-duration: 0.2s;
  -o-transition-duration: 0.2s;
  transition-duration: 0.2s;
  -webkit-transition-timing-function: ease-in;
  -moz-transition-timing-function: ease-in;
  -o-transition-timing-function: ease-in;
  transition-timing-function: ease-in;
}

.c100 .slice {
  position: absolute;
  width: 1em;
  height: 1em;
  clip: rect(0em, 1em, 1em, 0.5em);
}

.c100.p25 .bar {
  -webkit-transform: rotate(90deg);
  -moz-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  -o-transform: rotate(90deg);
  transform: rotate(90deg);
}

.c100:hover {
  cursor: default;
}

.c100.orange .bar,
.c100.orange .fill {
  border-color: #dd9d22 !important;
}

.c100.orange:hover>span {
  color: #dd9d22;
}
</style>