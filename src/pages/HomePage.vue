<script setup lang="ts">

import Service from "../components/Service.vue";
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
                <ul class="social-icon-list">
                  <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                  <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                  <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                  <li><a href="#"><i class="fab fa-youtube"></i></a></li>
                </ul>
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
              <a class="default-btn" href="about.html">Learn More <span></span></a>
            </div>
          </div>
        </div>
        <div class="col-lg-6 col-md-12">
          <div class="about-image">
            <img src="./../assets/img/about.jpg" alt="About image">
            <div class="years-design">
              <h2>23</h2>
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

  <!-- Start Counter Section -->
  <section class="counter-area section-padding">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 col-md-6 counter-item">
          <div class="single-counter">
            <div class="counter-contents">
              <h2>
                <span class="counter-number">23</span>
                <span>+</span>
              </h2>
              <h3 class="counter-heading">Years Helping Business</h3>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 counter-item">
          <div class="single-counter">
            <div class="counter-contents">
              <h2>
                <span class="counter-number">250</span>
                <span>+</span>
              </h2>
              <h3 class="counter-heading">Working Employees</h3>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 counter-item">
          <div class="single-counter">
            <div class="counter-contents">
              <h2>
                <span class="counter-number">4500</span>
                <span>+</span>
              </h2>
              <h3 class="counter-heading">Complete Projects</h3>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6 counter-item">
          <div class="single-counter">
            <div class="counter-contents">
              <h2>
                <span class="counter-number">3000</span>
                <span>+</span>
              </h2>
              <h3 class="counter-heading">Happy Customers</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Counter Section -->

  <!-- Start Testimonial Section -->
  <section class="testimonial-section pt-100 pb-50">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-title">
            <h6 class="sub-title">Our Testimonial</h6>
            <h2>Client Feedback</h2>
          </div>
        </div>
        <div class="col-lg-12 col-md-12">
          <div class="testimonial-slider owl-carousel owl-theme">
            <!-- testimonials item -->
            <div class="single-testimonial">
              <div class="rating-box">
                <ul>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                </ul>
              </div>
              <div class="testimonial-content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. enim ad minim veniam, quis nostrud exercitation.</p>
              </div>
              <div class="avatar">
                <img src="./../assets/img/testimonial-1.jpg" alt="testimonial images">
              </div>
              <div class="testimonial-bio">
                <div class="bio-info">
                  <h3>Saabir al-Obeid</h3>
                  <span>Turkey</span>
                </div>
              </div>
            </div>
            <!-- testimonials item -->
            <div class="single-testimonial">
              <div class="rating-box">
                <ul>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                </ul>
              </div>
              <div class="testimonial-content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. enim ad minim veniam, quis nostrud exercitation.</p>
              </div>
              <div class="avatar">
                <img src="./../assets/img/testimonial-2.jpg" alt="testimonial images">
              </div>
              <div class="testimonial-bio">
                <div class="bio-info">
                  <h3>Zahra Burnett</h3>
                  <span>United States</span>
                </div>
              </div>
            </div>
            <!-- testimonials item -->
            <div class="single-testimonial">
              <div class="rating-box">
                <ul>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                  <li><i class="fa fa-star"></i></li>
                </ul>
              </div>
              <div class="testimonial-content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. enim ad minim veniam, quis nostrud exercitation.</p>
              </div>
              <div class="avatar">
                <img src="./../assets/img/testimonial-3.jpg" alt="testimonial images">
              </div>
              <div class="testimonial-bio">
                <div class="bio-info">
                  <h3>Stevie Wills</h3>
                  <span>Germany</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Testimonial Section -->

  <!-- Start Team Section -->
  <section class="team-area section-padding">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-title">
            <h6 class="sub-title">Team Member</h6>
            <h2>Expert Team</h2>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="single-team-box">
            <div class="team-image">
              <img src="./../assets/img/team-1.jpg" alt="team">
              <div class="team-social-icon">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
              </div>
            </div>
            <div class="team-info">
              <h3>Ava Farrington</h3>
              <span>Founder, CEO</span>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="single-team-box">
            <div class="team-image">
              <img src="./../assets/img/team-2.jpg" alt="team">
              <div class="team-social-icon">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
              </div>
            </div>
            <div class="team-info">
              <h3>Kevin Haley</h3>
              <span>Co-Founder, CTO</span>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="single-team-box">
            <div class="team-image">
              <img src="./../assets/img/team-3.jpg" alt="team">
              <div class="team-social-icon">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
              </div>
            </div>
            <div class="team-info">
              <h3>Alishia Fulton</h3>
              <span>Chief Creative Officer</span>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-md-6">
          <div class="single-team-box">
            <div class="team-image">
              <img src="./../assets/img/team-4.jpg" alt="team">
              <div class="team-social-icon">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
              </div>
            </div>
            <div class="team-info">
              <h3>Lucas Martinez</h3>
              <span>Creative Director</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Team Section -->

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
        <div class="col-lg-4 col-md-6">
          <div class="blog-single-item">
            <div class="blog-image">
              <a href="single-blog.html">
                <img src="./../assets/img/blog-1.jpg" alt="image">
              </a>
            </div>
            <div class="blog-description">
              <ul class="blog-info">
                <li>
                  <a href="#"><i class="bi bi-person-circle"></i> Author</a>
                </li>
                <li>
                  <a href="#"><i class="bi bi-calendar-check"></i> 17 June 2024</a>
                </li>
              </ul>
              <div class="blog-text">
                <h3>
                  <a href="single-blog.html">
                    Demystifying the World of APIs: A Comprehensive Guide for Software Developers
                  </a>
                </h3>
                <p>Explore the fundamentals of APIs (Application Programming Interfaces),
                  breaking down the concept for beginners and delving into advanced topics</p>
                <div class="blog-btn"> <a href="single-blog.html" class="read-more"><i class="bi bi-arrow-right-short"></i> Read More</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="blog-single-item">
            <div class="blog-image">
              <a href="single-blog.html">
                <img src="./../assets/img/blog-2.jpg" alt="image">
              </a>
            </div>
            <div class="blog-description">
              <ul class="blog-info">
                <li>
                  <a href="#"><i class="bi bi-person-circle"></i> Author</a>
                </li>
                <li>
                  <a href="#"><i class="bi bi-calendar-check"></i> 20 June 2024</a>
                </li>
              </ul>
              <div class="blog-text">
                <h3>
                  <a href="single-blog.html">
                    Behind the Scenes: A Deep Dive into Agile Software Development Methodology
                  </a>
                </h3>
                <p>Share practical insights into implementing Agile practices, including Scrum and Kanban, with real-world examples of successful Agile projects</p>
                <div class="blog-btn">
                  <a href="single-blog.html" class="read-more"><i class="bi bi-arrow-right-short"></i> Read More</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="blog-single-item">
            <div class="blog-image">
              <a href="single-blog.html">
                <img src="./../assets/img/blog-3.jpg" alt="image">
              </a>
            </div>
            <div class="blog-description">
              <ul class="blog-info">
                <li>
                  <a href="#"><i class="bi bi-person-circle"></i> Author</a>
                </li>
                <li>
                  <a href="#"><i class="bi bi-calendar-check"></i> 25 June 2024</a>
                </li>
              </ul>
              <div class="blog-text">
                <h3>
                  <a href="single-blog.html">
                    From Legacy Systems to Modern Solutions: Strategies for Successful Software Migration Projects
                  </a>
                </h3>
                <p>Address the challenges and risks associated with migrating from legacy systems to modern solutions</p>
                <div class="blog-btn">
                  <a href="single-blog.html" class="read-more"><i class="bi bi-arrow-right-short"></i> Read More</a>
                </div>
              </div>
            </div>
          </div>
        </div>
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

  <!-- Start Partner section -->
  <section class="partner-section pt-100 pb-70">
    <div class="container">
      <div class="partner-title">
        <h6 class="sub-title">Trusted By Over 1500</h6>
        <h2>Our Customers</h2>
      </div>
      <div class="partner-list">
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-1.png" alt="image">
          </a>
        </div>
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-2.png" alt="image">
          </a>
        </div>
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-3.png" alt="image">
          </a>
        </div>
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-4.png" alt="image">
          </a>
        </div>
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-5.png" alt="image">
          </a>
        </div>
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-6.png" alt="image">
          </a>
        </div>
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-7.png" alt="image">
          </a>
        </div>
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-8.png" alt="image">
          </a>
        </div>
        <div class="partner-item">
          <a href="#0">
            <img src="./../assets/img/client-9.png" alt="image">
          </a>
        </div>
      </div>
    </div>
  </section>
  <!-- End Partner section -->


</div>
</template>

<style scoped>

</style>
