<template>
  <div class="section-6-main">
    <div class="container">
      <div class="row">
        <div class="col-md-2 col-12 d-none d-lg-block d-xl-block">
          <img src="../../public/logo.png" class="container-fluid logo" />
          <div class="mt-5 cont">
            <img src="../../public/row.png" class="container-fluid logo-2" />
          </div>
        </div>
        <div class="col-md-2 col-12"></div>
        <div class="col-md-2 col-12">
          <P class="heading-footer">About</P>
          <P>How it works</P>
          <P>Company</P>
          <P>Help and support</P>
        </div>
        <div class="col-md-2 col-12">
          <P class="heading-footer">For creators</P>
          <P>How can i get paid</P>
          <p>Beome a creator</p>
        </div>
        <div class="col-md-2 col-12">
          <p class="heading-footer">Learn</p>
          <P>Blog</P>
          <P>Cookies Policy</P>
          <P>Privacy Policy</P>
        </div>
        <div class="col-md-2 col-12">
          <p class="heading-footer">Support</p>
          <P>Service Status</P>
          <P>Report Abuse</P>
          <p>Dispute a payment</p>
        </div>

        <div class="col-md-2 col-12 d-lg-none d-xl-none text-center mt-5">
          <img src="../../public/logo.png" class="container-fluid logo" />
          <div class="mt-3">
            <img src="../../public/row.png" class="container-fluid logo-2" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.logo-2 {
  width: 88px;
  height: 24px;
}
.cont {
  margin-top: 90px !important;
}
.logo {
  width: 87.11px;
  height: 24.12px;
}
.section-6-main {
  margin-top: 120px;
  margin-bottom: 120px;
}

.heading-footer {
  font-size: 18px;
  font-weight: 700;
}

@media (min-width: 1024px) {
  .item {
    margin-top: 0;
    padding: 0.4rem 0 1rem calc(var(--section-gap) / 2);
  }

  i {
    top: calc(50% - 25px);
    left: -26px;
    position: absolute;
    border: 1px solid var(--color-border);
    background: var(--color-background);
    border-radius: 8px;
    width: 50px;
    height: 50px;
  }

  .item:before {
    content: ' ';
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    bottom: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:after {
    content: ' ';
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    top: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:first-of-type:before {
    display: none;
  }

  .item:last-of-type:after {
    display: none;
  }
}
</style>
