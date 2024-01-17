<script setup lang="ts">

</script>

<template>

  <!-- Start Navbar Section -->
  <div class="navbar-section">
    <div class="techvio-responsive-nav">
      <div class="container">
        <div class="techvio-responsive-menu">
          <div class="logo w-100">
            <router-link to="/" class="text-center">
              <span class="white-logo text-white">VEHITRADE</span>
              <span class="black-logo text-black">VEHITRADE</span>
            </router-link>
          </div>
        </div>
      </div>
    </div>
    <div class="techvio-nav">
      <div class="container">
        <nav class="navbar navbar-expand-md navbar-light">
          <router-link to="/" class="navbar-brand text-white font-weight-bold">
         <b> VEHITRADE</b>
          </router-link>
          <div class="collapse navbar-collapse mean-menu" id="navbarSupportedContent">
            <ul class="navbar-nav">
              <li class="nav-item">
                <router-link to="/" class="nav-link">Home</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/about" class="nav-link">About Us</router-link>
              </li>

              <li class="nav-item">
                <router-link to="/blogs" class="nav-link">Blogs</router-link>
              </li>

              <li class="nav-item">
                <router-link to="/contact" class="nav-link">Contact Us</router-link>
              </li>
            </ul>
            <div class="other-option">
              <router-link class="default-btn" to="/contact">Get IT Support <span></span></router-link>
            </div>
          </div>
        </nav>
      </div>
    </div>
  </div>
  <!-- End Navbar Section -->
</template>

<style scoped>

</style>
