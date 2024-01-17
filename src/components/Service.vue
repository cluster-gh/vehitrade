<script setup lang="ts">

</script>

<template>
  <div class="single-services-item">
    <div class="services-icon">
      <i :class="$attrs.icon ?? 'flaticon-development'"></i>
    </div>
    <h3>{{$attrs.title}}</h3>
    <p>{{ $attrs.text }}</p>
    <div class="services-btn">
      <a href="#" class="read-more"><i class="bi bi-arrow-right-short"></i> Read More</a>
    </div>
  </div>
</template>

<style scoped>

</style>
