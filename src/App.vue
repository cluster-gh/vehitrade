<script setup lang="ts">

import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="">
    <Header/>
    <div class="">
      <router-view></router-view>
    </div>
    <Footer />
  </div>

</template>

<style scoped>

</style>
