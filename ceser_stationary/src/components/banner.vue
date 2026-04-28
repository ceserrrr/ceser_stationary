<template>
  <div class="mt-4 w-full">
    <div
      class="relative bg-gray-200 overflow-hidden shadow-lg"
      >
      <!-- Dark overlay for better text readability -->
      <div class="absolute inset-0 bg-white opacity-20"></div>
      
      <div class="relative z-10 flex flex-col md:flex-row items-center justify-between px-6 md:px-12 py-8 md:py-12">
        <!-- Left Content -->
        <div class="md:w-1/2 mb-6 md:mb-0">
          <!-- Logo -->
          <div class="mb-6">
            <img src="../assets/logo.png" alt="CESER Logo" class="h-16 w-auto" />
          </div>

          <!-- Main Heading -->
          <h1 class="text-3xl md:text-4xl lg:text-5xl font-bold text-teal-700 mb-4 leading-tight">
            TINGKATKAN GAYA<br />KERJA & BELAJARMU
          </h1>

          <!-- Subtitle -->
          <p class="text-gray-600 text-base md:text-lg mb-8 leading-relaxed">
            Temukan Koleksi Alat Tulis & Sepatu Eksklusif Terbaru
          </p>

          <!-- CTA Button -->
          <button
            class="px-8 py-3 bg-teal-600 hover:bg-teal-700 text-white font-bold rounded-full transition duration-300 ease-in-out transform hover:scale-105 shadow-md"
          >
            JELAJAHI SEKARANG
          </button>
        </div>

        <!-- Right Image (Banner Image) -->
        <div class="hidden md:flex md:w-1/2 justify-end">
          <img src="../assets/banner.png" alt="Promotional Banner" class="h-64 lg:h-80 w-auto object-contain" />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import bannerImage from '../assets/banner.png'
</script>

<style scoped>
/* Additional custom styles if needed */
</style>