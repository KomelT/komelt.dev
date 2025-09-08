<script setup lang="ts">
import Experience from './ExperienceEducation.vue';
import BigTitle from './BigTitle.vue';
</script>
<template>
  <div class="page" id="about">
    <BigTitle title="ABOUT ME" subtitle="Resume" />
    <div id="about" class="about">
      <div class="main-content">
        <div class="container">
          <div class="row">
            <!-- Personal Info Starts -->
            <div class="col-12 col-lg-5 col-xl-6" style="margin: 0 auto;">
              <div class="row">
                <div class="col-12">
                  <h3 class="text-uppercase poppins-font text-center custom-title mb-0 ft-wt-600">personal infos</h3>
                </div>
                <div class="col-12 d-block d-sm-none">
                  <img src="../assets/img/tilen_komel500x500.jpg" class="img-fluid main-img-mobile" alt="my picture">
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
                      <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">{{ new
                        Date().getFullYear() - 2002 }} Years</span>
                    </li>
                    <li>
                      <span class="title">Nationality: </span>
                      <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">Slovenian</span>
                    </li>
                    <li>
                      <span class="title">GitHub: </span>
                      <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block"><a
                          href="https://github.com/komelt" target="_blank">github.com/komelt</a></span>
                    </li>
                  </ul>
                </div>
                <div class="col-6">
                  <ul class="about-list list-unstyled open-sans-font">
                    <li>
                      <span class="title">Mastodon: </span>
                      <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block"><a
                          href="https://toot.tux.si/@komelt" target="_blank">@komelt.toot.tux.si</a></span>
                    </li>
                    <li>
                      <span class="title">Email: </span>
                      <span class="value d-block d-sm-inline-block d-lg-block d-xl-inline-block">me@komelt.dev</span>
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
                <div class="col-12 mt-3">
                  <a class="button" href="#">
                    <span class="button-text">View CV</span>
                    <span class="button-icon fa fa-download"></span>
                  </a>
                </div>
              </div>
            </div>
            <!-- Personal Info Ends -->
          </div>
          <hr class="separator mt-5">
          <Experience />
        </div>
      </div>
    </div>
  </div>
</template>