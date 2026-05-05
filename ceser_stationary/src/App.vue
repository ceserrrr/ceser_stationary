<script setup>
import Navbar from './components/navbar.vue'
import Banner from './components/banner.vue'
import Card from './components/card.vue'
</script>

<template>
  <Navbar />
  <Banner />
  <div class="mt-8 mb-6 flex justify-center gap-4">
    <Card />
    <Card />
    <Card />
    <Card />
  </div>
</template>
