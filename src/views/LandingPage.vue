<template>
  <main class="main-wrapper">
    <!-- Start Slider Area -->
    <div class="axil-slider-area axil-slide-activation position-relative">
      <!-- Start Single Slide -->
      <div
        class="axil-slide slide-style-5 theme-gradient-8 d-flex align-items-center"
      >
        <div class="container">
          <div class="row align-items-center w-100">
            <div class="col-lg-8 col-12">
              <div class="content">
                <div class="inner">
                  <h1
                    class="axil-display-1 mb--40 wow slideFadeInUp"
                    data-wow-duration="1s"
                    data-wow-delay="500ms"
                  >
                    Tenant Service <br />
                    Meets
                    <br/>
                    Property Management
                  </h1>
                  <router-link
                    class="axil-button btn-large btn-transparent wow slideFadeInUp"
                    data-wow-duration="1s"
                    data-wow-delay="800ms"
                    href="/services"><span class="button-text">View Features</span><span class="button-icon"></span></router-link>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Start Contact Form -->
        <div class="contact-form-wrapper">
          <div class="axil-contact-form contact-form-style-1">
            <h3 class="title">Request A Demo</h3>
            <form action="#">
              <div class="form-group">
                <input type="text" />
                <label>Name</label>
                <span class="focus-border"></span>
              </div>
              <div class="form-group">
                <input type="email" />
                <label>Email</label>
                <span class="focus-border"></span>
              </div>
              <div class="form-group">
                <input type="text" />
                <label>Company</label>
                <span class="focus-border"></span>
              </div>
              <div class="form-group">
                <input type="text" />
                <label>Phone</label>
                <span class="focus-border"></span>
              </div>
              <div class="form-group">
                <button class="axil-button btn-large btn-transparent w-100">
                  <span class="button-text text-uppercase">Request a Demo</span
                  ><span class="button-icon"></span>
                </button>
              </div>
            </form>
            <div class="callto-action-wrapper text-center">
              <span class="text">Or call us now</span>
              <span
                ><i class="fal fa-phone-alt"></i>
                <a href="#">(256) 702 173540</a></span
              >
            </div>
          </div>
        </div>
        <!-- End Contact Form -->
      </div>
      <!-- End Single Slide -->
    </div>
    <!-- End Slider Area -->

   
  </main>
</template>

<script>
export default {
  name: "Landing"
};
</script>