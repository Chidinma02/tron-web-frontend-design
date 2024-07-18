<script setup></script>

<template>
  <div class="main">
    <div class="container">
      <nav class="navbar navbar-expand-lg">
        <a class="navbar-brand" href="#"><img src="/logo.png" class="img-fluid logo" /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <img src="../../public/burger.png" alt="Menu" class="custom-toggler-icon" />
        </button>

        <div class="collapse navbar-collapse py-2 poppins-regular" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Explore </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Company</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Support</a>
            </li>
          </ul>
          <ul class="navbar-nav my-2 my-lg-0 ms-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Become a member </a>
            </li>
          </ul>
          <form class="form-inline">
            <button type="button" class="btn btn-dark btn-primary button">sign in</button>
          </form>
        </div>
      </nav>

      <div class="row">
        <div class="col-lg-8 col-md-10 col-12">
          <h1 class="landing-text poppins-bold">
            Learn from your favorite creators about <span class="fanta">fantasy reports</span>
          </h1>

          <button
            type="button"
            class="btn btn-dark btn-primary button-two d-none d-lg-block d-xl-block d-md-block"
          >
            Get Started
          </button>
        </div>
        <!-- <div class="col-lg-4 col-md-2- col-12"></div> -->
      </div>

      <div class="d-lg-none d-xl-none d-md-none">
        <!-- <p>This text is visible on small screens to tablets, but hidden on larger screens.</p> -->
        <div class="row">
          <div class="col-6"></div>
          <div class="col-6"><img src="/home-elem.png " class="img-fluid elem" /></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.custom-toggler-icon {
  width: 30px; /* Adjust the width as needed */
  height: 30px; /* Adjust the height as needed */
}

.navbar-toggler {
  border: none; /* Remove the default border */
  padding: 0; /* Remove default padding */
}
.main {
  padding-bottom: 50px;
}
.logo {
  width: 96px;
  height: 32px;
}
.nav-link {
  color: #2b2730;
  font-size: 16px;
  line-height: 24px;
  font-weight: 500;
}

@media (min-width: 768px) {
  .main {
    background-image: url('/banner.png');
    height: 100vh;
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Do not repeat the image */
    background-size: cover; /* Resize the background image to cover the entire container */
  }
  .landing-text {
    font-weight: 700;
    margin-top: 230px;
    font-size: 72px;
    /* line-height: 80px; */
  }
  .fanta {
    color: #ffb84c;
    font-weight: 700;
    margin-top: 300px;
    font-size: 72px;
  }
  .button-two {
    width: 214px;
    height: 74px;
    border-radius: 100px;
    padding: 16px, 32px, 16px, 32px;
    font-weight: 500;
    font-size: 20px;
    border-bottom: 8px solid #ffb84c;
    margin-top: 5px;
  }
}

/* small screen */
@media (min-width: 320px) and (max-width: 767px) {
  .elem {
    margin-top: -28px;
  }
  .main {
    background-color: white !important;
    background-image: none;
  }
  .landing-text {
    font-weight: 700;
    margin-top: 50px !important;
    font-size: 32px;
    /* line-height: 80px; */
  }
  .fanta {
    color: #ffb84c;
    font-weight: 700;
    margin-top: 300px;
    font-size: 32px;
  }
}
.button {
  /* border-radius: 23px;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: 20px;
  padding-right: 20px; */
  padding: 16px, 32px, 16px, 32px;
  width: 112px;
  height: 52px;
  border-radius: 100px;
  font-weight: 500;
  font-size: 14px;
}
</style>
