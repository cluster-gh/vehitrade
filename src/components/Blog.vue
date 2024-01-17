<script setup lang="ts">

const props = defineProps(['blog'])

</script>

<template>
  <router-link :to="'/blogs/'+blog.id">
    <div class="blog-single-item">
      <div class="blog-image">
          <img :src="`/assets/img/blog-${props.blog.id}.jpg`" alt="image">
      </div>
      <div class="blog-description">
        <ul class="blog-info">
          <li>
            <a href="#"><i class="bi bi-person-circle"></i>{{blog.author}}</a>
          </li>
          <li>
            <a href="#"><i class="bi bi-calendar-check"></i>{{ blog.date }}</a>
          </li>
        </ul>
        <div class="blog-text">
          <h3>
            <router-link :to="'/blogs/'+blog.id">
              {{ blog.title }}
            </router-link>
          </h3>
          <p>
            {{blog.content}}
          </p>
          <div class="blog-btn">   <router-link :to="'/blogs/'+blog.id" class="read-more"><i class="bi bi-arrow-right-short"></i> Read More</router-link>
          </div>
        </div>
      </div>
    </div>
  </router-link>

</template>

<style scoped>

</style>
