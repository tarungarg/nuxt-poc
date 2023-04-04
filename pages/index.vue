<template>
  <div class="home-section">
    <div class="top-b"></div>
    <div class="login">
      <div class="login-text">
        <a href="#" class="link">Login</a>
      </div>
    </div>
    <div class="job-banner">
      <div class="job-banner-title">Deine Job website</div>
      <div class="job-banner-img"></div>
      <div class="border">
        <div class="job-banner-btn">
          <a href="#" class="btn">Kostenlos Registrieren</a>
        </div>
      </div>
    </div>
    <div class="white-bg-section">
      <div class="job-tiles">
        <div class="tile tile-1">Arbeitnehmer</div>
        <div class="tile tile-2">Arbeitgeber</div>
        <div class="tile tile-3">Temporärbüro</div>
      </div>
      <div class="sec-1">
        <div class="sec-1-title">
          Drei einfache Schritte zu deinem neuen Job
        </div>
        <div class="sec-1-img"></div>
        <div class="sec-1-txt">
          <div class="sec-1-number"><span>1.</span></div>
          <div class="sec-1-text">Erstellen dein Lebenslauf</div>
        </div>
      </div>
    </div>
    <div class="sec-2">
      <div class="custom-shape-divider-top-1652113377">
        <svg
          data-name="Layer 1"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 1200 120"
          preserveAspectRatio="none"
        >
          <path
            d="M985.66,92.83C906.67,72,823.78,31,743.84,14.19c-82.26-17.34-168.06-16.33-250.45.39-57.84,11.73-114,31.07-172,41.86A600.21,600.21,0,0,1,0,27.35V120H1200V95.8C1132.19,118.92,1055.71,111.31,985.66,92.83Z"
            class="shape-fill"
          ></path>
        </svg>
      </div>
      <div class="sec-2-text">
        <div class="sec-2-number">2.</div>
        <div class="sec-2-title">Erstellen ein Jobinserat</div>
      </div>
      <div class="sec-2-img"></div>
    </div>
    <div class="sec-3">
      <div class="custom-shape-divider-bottom-1652114159">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
          <path
            fill="#ffffff"
            fill-opacity="1"
            d="M0,224L60,192C120,160,240,96,360,74.7C480,53,600,75,720,90.7C840,107,960,117,1080,112C1200,107,1320,85,1380,74.7L1440,64L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"
          ></path>
        </svg>
        <!-- <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
          <path
            fill="#ffffff"
            fill-opacity="1"
            d="M0,224L60,192C120,160,240,96,360,74.7C480,53,600,75,720,90.7C840,107,960,117,1080,112C1200,107,1320,85,1380,74.7L1440,64L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"
          ></path>
        </svg> -->
      </div>
      <div class="sec-3-text">
        <div class="sec-3-number">3.</div>
        <div class="sec-3-title">Mit nur einem Klick bewerben</div>
      </div>
      <div class="sec-3-img"></div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>

<style scoped>
.custom-shape-divider-top-1652113377 {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  line-height: 0;
  transform: rotate(180deg);
}

.custom-shape-divider-top-1652113377 svg {
  position: relative;
  display: block;
  width: calc(100% + 1.3px);
  height: 39px;
}

.custom-shape-divider-top-1652113377 .shape-fill {
  fill: #ffffff;
}

.custom-shape-divider-bottom-1652114159 {
  position: absolute;
  top: -59px;
  width: 100%;
}

.custom-shape-divider-bottom-1652114159 svg {
  position: relative;
}

/* .custom-shape-divider-bottom-1652114159 .shape-fill {
  fill: #ffffff;
} */
.home-section {
  background: transparent linear-gradient(141deg, #ebf4ff 0%, #e6fffa 100%) 0%
    0% no-repeat padding-box;
  opacity: 1;
}
.login {
  top: 5px;
  left: 0px;
  height: 67px;
  /* UI Properties */
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px 3px 6px #00000029;
  border-radius: 0px 0px 12px 12px;
  opacity: 1;
}
.top-b {
  top: 0px;
  left: 0px;
  height: 5px;
  background: transparent linear-gradient(91deg, #319795 0%, #3182ce 100%) 0% 0%
    no-repeat padding-box;
  opacity: 1;
}
.login {
  display: flex;
  justify-content: flex-end;

  align-items: center;
}
.login-text {
  height: 19px;
  display: block;
  font: normal normal 600 14px/17px Lato;
  letter-spacing: 0.84px;
  color: #319795;
  opacity: 1;
  cursor: pointer;
  padding-right: 19px;
}

.link:hover {
  text-decoration: underline;
}

.job-banner {
  display: flex;
  flex-direction: column;
  align-content: center;
}

.job-banner-img {
  height: 360px;
  /* UI Properties */
  background: transparent url('~/assets/img/undraw_agreement_aajr.png')
    no-repeat center center;
  opacity: 1;
}

.job-banner-title {
  /* UI Properties */
  font: normal normal 600 42px/50px Lato;
  letter-spacing: 1.26px;
  color: #2d3748;
  opacity: 1;
  align-self: center;
  display: block;
  /* padding: 1px 80px; */
  text-align: center;
  margin-top: 18px;
  margin-left: 20px;
  margin-right: 20px;
}

.job-banner-btn {
  align-self: center;
  width: 320px;
  height: 40px;
  background: transparent linear-gradient(95deg, #319795 0%, #3182ce 100%) 0% 0%
    no-repeat padding-box;
  border-radius: 12px;
  text-align: center;
  opacity: 1;
  margin: auto;
  padding: 6px;
  margin-top: 24px;
}

.job-banner-btn a {
  /* UI Properties */
  text-align: center;
  font: normal normal 600 14px/17px Lato;
  letter-spacing: 0.84px;
  color: #e6fffa;
}

.border {
  height: 128px;
  /* UI Properties */
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px -1px 3px #00000033;
  border-radius: 12px 12px 0px 0px;
  opacity: 1;
}

.job-tiles {
  display: grid;
  grid-auto-flow: column;
  grid-template-columns: repeat(3, 160px [col-start]);
  height: 40px;
  margin-left: 20px;
  overflow-y: scroll;
}

.tile {
  display: flex;
  justify-content: center;
  align-items: center;
  font: normal normal 600 14px/17px Lato;
  letter-spacing: 0.84px;
  color: #e6fffa;
  opacity: 1;
}
.tile-1 {
  background: #81e6d9 0% 0% no-repeat padding-box;
  border-radius: 12px 0px 0px 12px;
  opacity: 1;
}
.tile-2 {
  background: #ffffff 0% 0% no-repeat padding-box;
  border: 1px solid #cbd5e0;
  color: #319795;
}

.tile-3 {
  background: #ffffff 0% 0% no-repeat padding-box;
  border: 1px solid #cbd5e0;
  color: #319795;
}

.sec-1 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-top: 30px;
  position: relative;
}

.sec-1::after {
  width: 208px;
  height: 208px;
  background: #f7fafc 0% 0% no-repeat padding-box;
  opacity: 0.5;
  content: '';
  position: absolute;
  border-radius: 50% 50%;
  margin-top: 174px;
  margin-left: -41px;
  z-index: 2;
}

.sec-1-img {
  height: 145px;
  /* UI Properties */
  background: transparent url('~/assets/img/undraw_Profile_data_re_v81r.png') 0%
    0% no-repeat padding-box;
  opacity: 1;
  margin-left: 27%;
  margin-top: 3%;
  z-index: 4;
}

.sec-1-title {
  text-align: center;
  font: normal normal 400 21px/25px Lato;
  letter-spacing: 0px;
  color: #4a5568;
  opacity: 1;
  margin: 0 40px;
  padding: 0 35px;
}

.sec-1-txt {
  display: flex;
  align-items: flex-end;
  height: 63px;
  gap: 21px;
  z-index: 4;
}

.sec-1-number {
  text-align: center;
  font: normal normal normal 130px/108px Lato;
  letter-spacing: 0px;
  color: #718096;
  opacity: 1;
  padding-left: 10px;
  flex-grow: 1;
}

.sec-1-text {
  font: normal normal normal 16px/19px Lato;
  letter-spacing: 0.47px;
  color: #718096;
  opacity: 1;
  flex-grow: 1;
}

.num-background {
  background: #f7fafc 0% 0% no-repeat padding-box;
  opacity: 0.5;
  width: 208px;
  height: 208px;
}
.white-bg-section {
  background: #ffffff;
  padding-top: 27px;
  padding-bottom: 20px;
  z-index: 1;
}

.sec-2 {
  height: auto;
  background: transparent linear-gradient(134deg, #e6fffa 0%, #ebf4ff 100%) 0%
    0% no-repeat padding-box;
  opacity: 1;
  display: flex;
  flex-direction: column;
  position: relative;
  padding-top: 22px;
  padding-bottom: 57px;
}

.sec-2-text {
  display: flex;
  flex-direction: row;
  align-items: flex-end;
  flex-wrap: nowrap;
  gap: 20px;
}

.sec-2-number {
  height: 156px;
  text-align: center;
  font: normal normal normal 130px/156px Lato;
  letter-spacing: 0px;
  color: #718096;
  margin-left: 35px;
  align-self: flex-end;
  flex-grow: 1;
}

.sec-2-title {
  font: normal normal normal 16px/19px Lato;
  letter-spacing: 0.47px;
  color: #718096;
  opacity: 1;
  align-self: center;
  justify-self: flex-start;
  flex-grow: 1;
  margin-top: 82px;
}

.sec-2-img {
  margin-left: 32%;
  width: 181px;
  height: 127px;
  background: transparent url('~/assets/img/undraw_task_31wc.png') 0% 0%
    no-repeat padding-box;
  opacity: 1;
}

.sec-3 {
  height: auto;
  background: #ffffff 0% 0% no-repeat padding-box;
  opacity: 1;
  display: flex;
  flex-direction: column;
  position: relative;
  padding-bottom: 30%;
}

.sec-3::after {
  width: 304px;
  height: 303px;
  background: #f7fafc 0% 0% no-repeat padding-box;
  opacity: 1;
  content: '';
  position: absolute;
  border-radius: 50% 50%;
  margin-top: -14%;
  margin-left: -15%;
  z-index: 2;
}

.sec-3-text {
  display: flex;
  flex-direction: row;
  align-items: flex-end;
  flex-wrap: nowrap;
  gap: 15px;
  z-index: 4;
  position: relative;
  top: -6%;
}

.sec-3-number {
  height: 156px;
  text-align: center;
  font: normal normal normal 130px/62px Lato;
  letter-spacing: 0px;
  color: #718096;
  margin-left: 54px;
  align-self: flex-start;
  flex-grow: 1;
  z-index: 4;
}

.sec-3-title {
  font: normal normal normal 16px/19px Lato;
  letter-spacing: 0.47px;
  color: #718096;
  opacity: 1;
  align-self: flex-start;
  justify-self: flex-start;
  flex-grow: 1;
  margin-right: 36px;
  z-index: 4;
  margin-top: 21px;
}

.sec-3-img {
  margin-left: 18%;
  width: 281px;
  height: 210px;
  /* UI Properties */
  background: transparent url('~/assets/img/undraw_personal_file_222m.png') 0%
    0% no-repeat padding-box;
  opacity: 1;
  margin-top: -95px;
  z-index: 4;
}
</style>
