<script setup lang="ts">

</script>

<template>
  <!-- Start Page Title Section -->
  <div class="page-title-area">
    <div class="d-table">
      <div class="d-table-cell">
        <div class="container">
          <div class="page-title-content">
            <h2>Contact</h2>
            <ul>
              <li><a href="index.html">Home</a>
              </li>
              <li>Contact</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- End Page Title Section -->

  <!-- Start Contact Section -->
  <div class="contact-section section-padding">
    <div class="container">
      <div class="section-title">
        <h6 class="sub-title">Let's Talk</h6>
        <h2>Contact Us</h2>
      </div>
      <div class="row align-items-center">
        <div class="col-lg-10 offset-lg-1">
          <div class="contact-form">
            <p class="form-message"></p>
            <form id="contact-form" class="contact-form form" action="phpmails.php" method="POST">
              <div class="row">
                <div class="col-lg-6 col-md-6">
                  <div class="form-group">
                    <input type="text" name="name" id="name" class="form-control" required placeholder="Your Name">
                  </div>
                </div>
                <div class="col-lg-6 col-md-6">
                  <div class="form-group">
                    <input type="email" name="email" id="email" class="form-control" required placeholder="Your Email">
                  </div>
                </div>
                <div class="col-lg-6 col-md-6">
                  <div class="form-group">
                    <input type="text" name="phone" id="phone" required class="form-control" placeholder="Your Phone">
                  </div>
                </div>
                <div class="col-lg-6 col-md-6">
                  <div class="form-group">
                    <input type="text" name="subject" id="subject" class="form-control" required placeholder="Your Subject">
                  </div>
                </div>
                <div class="col-lg-12 col-md-12">
                  <div class="form-group">
                    <textarea name="message" class="form-control" id="message" cols="30" rows="6" required placeholder="Your Message"></textarea>
                  </div>
                </div>
                <div class="col-lg-12 col-md-12">
                  <button type="submit" class="default-btn submit-btn">Send Message <span></span></button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- End Contact Section -->

  <!-- Start Map Section -->
  <div class="map-section">
    <div class="google-map">
      <iframe
          width="450"
          height="250"
          frameborder="0" style="border:0"
          referrerpolicy="no-referrer-when-downgrade"
          src="https://www.google.com/maps/embed/v1/place?key=AIzaSyBGSZ0tiKdD5iDMF105sgxJEsjtC-1dKTw&q=accra,ghana"
          allowfullscreen>
      </iframe>    </div>
  </div>
  <!-- End Map Section -->

</template>

<style scoped>

</style>
