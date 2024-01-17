<script setup lang="ts">

import Service from "../components/Service.vue";
import {blogs} from '../utils/data'
import Blog from "../components/Blog.vue";
</script>

<template>
<div>

  <!-- End Preloader Section -->


  <!-- Start Home Section -->
  <div class="home-section">
    <div class="d-table">
      <div class="d-table-cell">
        <div class="container">
          <div class="row align-items-center">
            <div class="col-lg-6 col-md-12">
              <div class="main-banner-content">
                <h1>IT Solutions & Business Services Company</h1>
                <p>
                  Software development agency dedicated to crafting cutting-edge solutions
                  that elevate businesses and delivering innovative and scalable software
                  tailored to meet your unique needs
                </p>
                <div class="banner-btn">
                  <a class="default-btn-one" href="services.html">Our Service <span></span></a>
                  <a class="default-btn-two" href="contact.html">Contact Us <span></span></a>
                </div>
              </div>
            </div>
            <div class="col-lg-6 col-md-12" data-tilt>
              <div class="banner-image">
                <img src="./../assets/img/home-font.png" alt="image">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="creative-shape">
      <img src="./../assets/img/home-bottom-shape.png" alt="svg shape">
    </div>
  </div>
  <!-- End Home Section -->

  <!-- Start Services Section -->
  <section class="services-section section-padding">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-title">
            <h6 class="sub-title">What We Provide</h6>
            <h2>Our Services</h2>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <Service title="Web Development"
                   text="Crafting responsive and innovative web solutions tailored to elevate your online presence."
          ></Service>
        </div>
        <div class="col-lg-4 col-md-6">
          <Service title="Digital Marketing"
                   text="Elevate your brand and reach new heights with our data-driven digital marketing strategies."
                   icon="flaticon-targeted-marketing" />
        </div>

        <div class="col-lg-4 col-md-6">
          <Service title="Startup Solutions"
                   text="Empowering startups with comprehensive solutions for success in a dynamic business landscape."
                   icon="flaticon-analytics" />
        </div>
        <div class="col-lg-4 col-md-6">
          <Service title="Networking Services"
                   text="Connecting businesses seamlessly with our top-tier networking services for optimal efficiency and performance."
                   icon="flaticon-super-intelligence" />
        </div>
        <div class="col-lg-4 col-md-6">
          <Service title="SEO Optimization"
                   text="Boost your online visibility and rankings with our expert SEO optimizations for sustainable digital growth."
                   icon="flaticon-code" />
        </div>
        <div class="col-lg-4 col-md-6">

          <Service title="Apps Development"
                   text="Transforming ideas into exceptional mobile experiences with our expert app development solutions."
                   icon="flaticon-mobile-app" />
        </div>
      </div>
    </div>
  </section>
  <!-- End Services Section -->

  <!-- Start About Section -->
  <section class="about-area bg-grey section-padding">
    <div class="container">
      <div class="row d-flex align-items-center">
        <div class="col-lg-6 col-md-12">
          <div class="about-content">
            <h6 class="sub-title">About Our Company</h6>
            <h2>Providing Your Business With A Quality IT Service is Our Passion</h2>
            <p>Fulfilling your business needs with a passion for delivering top-notch IT services.</p>
            <div class="skills">
              <div class="skill-item">
                <h6>IT Consulting <em>90%</em></h6>
                <div class="skill-progress">
                  <div class="progres" data-value="90%"></div>
                </div>
              </div>
              <div class="skill-item">
                <h6>Cloud Solutions <em>75%</em></h6>
                <div class="skill-progress">
                  <div class="progres" data-value="75%"></div>
                </div>
              </div>
              <div class="skill-item">
                <h6>Managed IT Service <em>85%</em></h6>
                <div class="skill-progress">
                  <div class="progres" data-value="85%"></div>
                </div>
              </div>
            </div>
            <div class="about-btn-box">
              <router-link class="default-btn" to="/about">Learn More <span></span></router-link>
            </div>
          </div>
        </div>
        <div class="col-lg-6 col-md-12">
          <div class="about-image">
            <img src="./../assets/img/about.jpg" alt="About image">
            <div class="years-design">
              <h2>5+</h2>
              <h5>Years Of Experience</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End About Section -->

  <!-- Start Overview Section -->
  <section class="overview-section section-padding">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-6">
          <div class="overview-image">
            <img src="./../assets/img/choose-1.png" alt="image">
          </div>
        </div>
        <div class="col-lg-6">
          <div class="overview-content">
            <h6 class="sub-title">Why Choose Us?</h6>
            <h2>Safeguard Your Brand with Cyber Security and IT Solutions</h2>
            <p>Fortify your brand's resilience with robust cybersecurity and tailored IT solutions.</p>
            <ul class="features-list">
              <li> <span>Remote IT Assistance</span></li>
              <li> <span>Cloud Services</span></li>
              <li> <span>Managed IT Service</span></li>
              <li> <span>IT Security Services</span></li>
              <li> <span>Practice IT Management</span></li>
              <li> <span>Solving IT Problems</span></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Overview Section -->

  <!-- Start Overview Section -->
  <section class="overview-section pt-50 pb-100">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-6">
          <div class="overview-content">
            <h6 class="sub-title">WHY TRUST US?</h6>
            <h2>Achieve Digital Transformation For Your Retail Business Services</h2>
            <p>Embark on a journey of digital transformation to redefine and elevate your organizational capabilities.</p>
            <ul class="features-list">
              <li> <span>Protect your Business</span></li>
              <li> <span>Network Security</span></li>
              <li> <span>Data Security</span></li>
              <li> <span>Small Business Owners</span></li>
              <li> <span>Running your Business</span></li>
              <li> <span>Network Monitoring</span></li>
            </ul>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="overview-image-2">
            <img src="./../assets/img/choose-2.png" alt="image">
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Overview Section -->

  <!-- Start Blog Section -->
  <section class="blog-section bg-grey pt-100 pb-70">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-title">
            <h6 class="sub-title">Blog & Article</h6>
            <h2>Recent Blog</h2>
          </div>
        </div>

        <template v-for="blog in blogs.slice(0,3)" :key="blog.id">
          <div class="col-lg-4 col-md-6">
          <Blog :blog="blog"></Blog>
          </div>
        </template>
    
      </div>
    </div>
  </section>
  <!-- End Blog Section -->

  <!-- Start Hire Section -->
  <section class="hire-section">
    <div class="container">
      <div class="row">
        <div class="col-lg-8 offset-lg-2 col-md-12">
          <div class="hire-content">
            <h6 class="sub-title">Want to work with us?</h6>
            <h2>Digitally Transform & Grow Your Business</h2>
            <p>
              Empower your business through digital transformation,
              unlocking growth opportunities and embracing the future. Transform today, thrive tomorrow.
            </p>
            <div class="hire-btn">
              <a class="default-btn" href="tel:+233248284049">Call Now<span></span></a>
              <router-link to="/contact" class="default-btn-one" >Contact Us<span></span></router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Hire Section -->


</div>
</template>

<style scoped>

</style>
