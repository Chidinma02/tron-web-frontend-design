<script setup>
import WelcomeItem from './section3.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div class="container">
    <div class="d-md-none d-lg-none d-xl-none negative-margin-img">
      <img src="../../public/img (1).png" class="img-fluid im" />
    </div>
  </div>
  <div class="main-section-two">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <h1 class="get-direct-h1 mt-5 poppins-bold text-break">Get direct</h1>
          <h1 class="knowledge poppins-bold text-break">knowledge and insight.</h1>
        </div>
      </div>

      <div class="row">
        <div class="col-md-4 col-12 mt-5">
          <img src="/img-card.png" class="img-fluid" />
        </div>
        <div class="col-md-4 col-12 mt-5">
          <img src="/img-card (1).png" class="img-fluid" />
        </div>
        <div class="col-md-4 col-12 mt-5">
          <img src="/img-card (2).png" class="img-fluid" />
        </div>
      </div>

      <div class="row gallery">
        <div class="col-md-7 col-12">
          <div class="row">
            <div class="col-12 col-md-4 small-center">
              <h1 class="get-direct-h1">300</h1>
              <p class="cl">creators</p>
            </div>
            <div class="col-12 col-md-4 small-center">
              <h1 class="get-direct-h1">14.4k</h1>
              <p class="cl">users</p>
            </div>
            <div class="col-12 col-md-4 small-center">
              <h1 class="get-direct-h1">9.11k</h1>
              <P class="cl">session</P>
            </div>
          </div>
        </div>
        <div class="col-md-1 col-12"></div>
        <div class="col-md-4 col-12">
          <div class="">
            <div class="row d-flex justify-content-between">
              <div class="col-md-8 col-9">
                <p class="cl">Explore the market place</p>
              </div>
              <div class="col-md-4 col-3 d-flex justify-content-end">
                <img src="/arrow-icon.png" class="img-fluid img-arrow im-cl" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.im {
}
.negative-margin-img {
  position: absolute;
  top: 38%;
  width: 90%;
  /* position: absolute;
  top: 800px; */
  /* right: 0; */
}
.img-arrow {
  width: 64px;
  height: 64px;
}
.cl {
  color: white;
  font-weight: 400;
  font-size: 24px;
  line-height: 40px;
  font-family: Poppins;
}
.gallery {
  margin-top: 200px;
}

@media (min-width: 320px) and (max-width: 767px) {
  .main-section-two {
    padding-top: 100px;
  }
}
.main-section-two {
  background-color: #2b2730;
}
.knowledge {
  color: #ffffff;
  font-weight: 700;
  font-size: 56px;
  font-family: Poppins;
  /* font-weight: 700;
  font-size: 64px;  */
}
.get-direct-h1 {
  color: #ffb84c;
  font-weight: 700;
  font-size: 56px;
  font-family: Poppins;
}
@media (min-width: 320px) and (max-width: 767px) {
  .small-center {
    text-align: center;
  }

  .cl {
    font-size: 16px;
  }

  .im-cl {
    width: 32px;
    height: 32px;
    margin-top: 8px;
  }
}
</style>
