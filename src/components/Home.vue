<template>
  <div class="home">
    <section class="
				container-fluid
				main-container
				container-home
				p-0
				revealator-slideup revealator-once revealator-delay1
			">
      <div class="color-block d-none d-lg-block"></div>
      <div class="row home-details-container align-items-center">
        <div class="col-lg-4 bg position-absolute d-none d-lg-block"></div>
        <div class="col-12 col-lg-8 offset-lg-4 home-details text-left text-sm-center text-lg-left">
          <div>
            <img src="../assets/img/tilen_komel500x500.jpg" class="img-fluid main-img-mobile d-none d-sm-block d-lg-none"
              alt="Tilen Komel" title="Tilen Komel" />
            <h6 class="text-uppercase open-sans-font mb-0 d-block d-sm-none d-lg-block">
              hi there !
            </h6>
            <h1 class="text-uppercase poppins-font"><span>I'm</span> Tilen Komel</h1>
            <p class="open-sans-font">
              I'm a Slovenian based front‑end, back‑end & Wordpress developer focused on crafting
              clean & user‑friendly experiences. I am passionate about building excellent software
              that improves the lives of those around me.
            </p>
            <a href="#about" class="btn btn-about">more about me</a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<style scoped>
.home .color-block {
  position: absolute;
  height: 200%;
  width: 100%;
  transform: rotate(-15deg);
  left: -83%;
  top: -50%;
}

.home .bg {
  background-image: url(../assets/img/tilen_komel1020x610.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: top;
  height: calc(100vh - 60px);
  z-index: 111;
  border-radius: 15px;
  left: 30px;
  top: 30px;
  box-shadow: 0 0 7px rgba(0, 0, 0, 0.9);
}

.home .container-home {
  display: flex;
  align-items: center;
  min-height: 100%;
}

.home .home-details>div {
  max-width: 550px;
  margin: 0 auto;
}

.home .home-details h1 {
  font-size: 45px;
  line-height: 45px;
  font-weight: 700;
  margin: 18px 0 10px;
}

.home .home-details h1 span {
  color: #fff;
  font-weight: 600;
}

.home .home-details h6 {
  color: #eee;
  font-size: 22px;
  font-weight: 400;
  display: block;
}

.home .home-details p {
  margin: 10px 0 23px;
  font-size: 16px;
  line-height: 32px;
}

@media (max-width: 1100px) and (min-width: 992px) {
  .home .home-details>div {
    max-width: 450px;
  }
}

@media (min-width: 1600px) {
  .home .home-details>div {
    max-width: 600px;
  }
}

@media (min-width: 992px) {
  .home .home-details-container {
    width: 100%;
    height: 100vh;
  }

  body.home {
    overflow: hidden;
  }
}

@media (max-width: 991px) {
  .btn {
    padding: 0 28px;
  }

  body.home {
    padding: 25px;
  }

  body.home .main-container {
    padding: 30px 0 !important;
  }

  .home .home-details-container {
    margin: 0 auto;
  }

  .home .home-details {
    padding: 0;
  }

  .main-img-mobile {
    border-radius: 50%;
    width: 270px;
    height: 270px;
    border: 4px solid #252525;
    margin: 0 auto 25px;
    display: block;
  }

  .home .home-details h1 {
    font-size: 38px;
    line-height: 38px;
    margin: 29px 0 13px;
  }

  .home .home-details p {
    margin: 10px 0 23px;
    font-size: 15px;
    line-height: 30px;
  }
}

@media (max-width: 767px) {
  .home .home-details p {
    font-size: 14px;
    line-height: 28px;
  }
}

@media (max-width: 576px) {
  .home #menuToggle {
    right: 25px;
    top: 25px;
    padding: 17px 0 0 13px;
  }

  .main-img-mobile {
    width: 230px;
    height: 230px;
  }

  .home .home-details h1 {
    font-size: 29px;
    line-height: 29px;
    margin: 18px 0 13px;
  }

  .home .home-details h6 {
    font-size: 19px;
  }
}
</style>