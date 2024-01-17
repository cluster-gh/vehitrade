<script setup lang="ts">

</script>

<template>
  <!-- Start Footer & Subscribe Section -->
  <section class="footer-subscribe-wrapper">
    <!-- Start Subscribe Section -->
    <div class="subscribe-area">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-6 col-md-6">
            <div class="subscribe-content">
              <h2>Sign Up Our Newsletter</h2>
              <p>We Offer An Informative Monthly Technology Newsletter - Check It Out.</p>
            </div>
          </div>
          <div class="col-lg-6 col-md-6">
            <form class="newsletter-form">
              <input type="email" class="input-newsletter" name="email" placeholder="Enter Your Email" required autocomplete="off">
              <button type="submit">Subscribe Now</button>
            </form>
          </div>
        </div>
      </div>
    </div>
    <!-- End Subscribe Section -->
    <!-- Start Footer Section -->
    <div class="footer-area ptb-100">
      <div class="container">
        <div class="row">
          <div class="col-lg-4 col-md-6 col-sm-6">
            <div class="single-footer-widget">
              <a class="footer-logo text-white" href="#">
                <b>VEHITRADE</b>
               
              </a>
              <p>
                We are a dynamic software development agency dedicated to crafting cutting-edge solutions
                that elevate businesses. With a passionate team of skilled developers, we specialize in delivering
                innovative and scalable software tailored to meet your unique needs
              </p>
          
            </div>
          </div>
          <div class="col-lg-2 col-md-6 col-sm-6">
            <div class="single-footer-widget">
              <div class="footer-heading">
                <h3>Our Services</h3>
              </div>
              <ul class="footer-quick-links">
                <li><a href="#">Startup Solutions</a></li>
                <li><a href="#">Web Development</a></li>
                <li><a href="#">Networking Services</a></li>
                <li><a href="#">SEO Optimization</a></li>
                <li><a href="#">Apps Development</a></li>
              </ul>
            </div>
          </div>
          <div class="col-lg-2 col-md-6 col-sm-6">
            <div class="single-footer-widget">
              <div class="footer-heading">
                <h3>Useful Links</h3>
              </div>
              <ul class="footer-quick-links">
                <li><router-link to="/about" class="nav-link">About Us</router-link></li>
                <li><router-link to="/contact" class="nav-link">Contact Us</router-link></li>

                <li><router-link to="/contact" class="nav-link">Privacy Policy</router-link></li>
                <li><router-link to="/contact" class="nav-link">Terms & Conditions</router-link></li>
              </ul>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-6">
            <div class="single-footer-widget">
              <div class="footer-heading">
                <h3>Contact Info</h3>
              </div>
              <div class="footer-info-contact">
                <i class="flaticon-phone-call"></i>
                <h3>Phone</h3>
                <span><a href="tel:233248284049">+233 24 828 4049</a></span>
              </div>
              <div class="footer-info-contact">
                <i class="flaticon-envelope"></i>
                <h3>Email</h3>
                <span><a href="mailto:demo@example.com">ewave80@gmail.com</a></span>
              </div>
              <div class="footer-info-contact">
                <i class="flaticon-placeholder"></i>
                <h3>Address</h3>
                <span>Tema, Accra</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End Footer Section -->
  </section>
  <!-- End Footer & Subscribe Section -->

  <!-- Start Copy Right Section -->
  <div class="copyright-area">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-6 col-md-6">
          <p><i class="far fa-copyright"></i> 2024 VehiTrade - All Rights Reserved.</p>
        </div>
        <div class="col-lg-6 col-md-6">
          <ul>
            <li><a href="terms-condition.html">Terms & Conditions</a></li>
            <li><a href="privacy-policy.html">Privacy Policy</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- End Copy Right Section -->

</template>

<style scoped>

</style>
