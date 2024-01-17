<script setup lang="ts">

import {authors, randomize} from "../utils";
import {blogs} from '../utils/data'
import Blog from "../components/Blog.vue";
</script>

<template>
  <!-- Start Page Title Section -->
  <div class="page-title-area item-bg1">
    <div class="d-table">
      <div class="d-table-cell">
        <div class="container">
          <div class="page-title-content">
            <h2>Blogs</h2>
            <ul>
              <li><router-link to="/">Home</router-link>
              </li>
              <li>Blogs</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- End Page Title Section -->

  <!-- Start Blog Section -->
  <section class="blog-section section-padding">
    <div class="container">
      <div class="row">
        <template v-for="blog in blogs" :key="blog.id">
          <div class="col-lg-4 col-md-6">
          <Blog :blog="blog"></Blog>
          </div>
        </template>

        <div class="col-lg-12 col-md-12">
          <div class="pagination-area"> <a href="#" class="prev page-numbers"><i class="fas fa-angle-left"></i></a>
            <a href="#" class="page-numbers">1</a>
            <span class="page-numbers current" aria-current="page">2</span>
            <a href="#" class="page-numbers">3</a>
            <a href="#" class="page-numbers">4</a>
            <a href="#" class="next page-numbers"><i class="fas fa-angle-right"></i></a>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Blog Section -->

</template>

<style scoped>

</style>
