<template>
  <div class="row">
    <div class="col-12">
      <h3 class="text-uppercase poppins-font pb-5 mb-0 text-left text-sm-center custom-title ft-wt-600">Experience
        <span>&</span> Education
      </h3>
    </div>
    <div class="col-lg-6 m-15px-tb">
      <div class="resume-box">
        <ul>
          <li v-for="(item, index) in exEdFirstHalf" :key="index">
            <div class="icon">
              <i :class="item.icon"></i>
            </div>
            <span class="time open-sans-font text-uppercase">{{ item.time }}</span>
            <h5 class="poppins-font text-uppercase">{{ item.title }} <span class="place open-sans-font">{{ item.place
                }}</span>
            </h5>
            <p class="open-sans-font">{{ item.description }}</p>
          </li>
        </ul>
      </div>
    </div>
    <div class="col-lg-6 m-15px-tb">
      <div class="resume-box">
        <ul>
          <li v-for="(item, index) in exEdSecondHalf" :key="index">
            <div class="icon">
              <i :class="item.icon"></i>
            </div>
            <span class="time open-sans-font text-uppercase">{{ item.time }}</span>
            <h5 class="poppins-font text-uppercase">{{ item.title }} <span class="place open-sans-font">{{ item.place
                }}</span>
            </h5>
            <p class="open-sans-font">{{ item.description }}</p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">

type exEdType = {
  icon: "fa fa-graduation-cap" | "fa fa-briefcase"
  time: string
  title: string
  place: string
  description: string
}

const exEdList: exEdType[] = [
  {
    icon: "fa fa-graduation-cap",
    time: "2021 - present",
    title: "Started studying CS",
    place: "FRI - UL",
    description: "Currently studying at Faculty of Computer and Information Science, University of Ljubljana. Study program: Computer and information science."
  },
  {
    icon: "fa fa-graduation-cap",
    time: "2017 - 2021",
    title: "Graduated from high school",
    place: "ERŠ - ŠCNG",
    description: " Graduated as gold high school graduate from vocational matura. School: School centre Nova Gorica, Electrical engineering and computer science school Educationa program: Computer technician "
  },
  {
    icon: "fa fa-briefcase",
    time: "2020 - present",
    title: "Homelab",
    place: "Home",
    description: "To expand my knowledge about servers, Linux server and hosting, I bought my first server HP Proliant DL380."
  },
  {
    icon: 'fa fa-briefcase',
    time: '2020 - present',
    title: 'Student work',
    place: 'Topis Mojca Babuder s.p.',
    description: 'Currently working at Topis Mojca Babuder s.p., I am working with Wordpress sites and servers.'
  },
  {
    icon: 'fa fa-briefcase',
    time: '2018 and 2019',
    title: 'internship',
    place: 'Gostol-Gopan d.o.o.',
    description: 'I had two week internship at Gostol-Gopan d.o.o. where I was working with networking equipment.'
  }
]

const exEdFirstHalf = exEdList.slice(0, Math.ceil(exEdList.length / 2));
const exEdSecondHalf = exEdList.slice(Math.ceil(exEdList.length / 2));

</script>