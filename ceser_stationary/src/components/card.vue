<template>
  <div class="mt-8 mx-4">
    <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition-shadow duration-300 max-w-xs">
      <!-- Product Image Container -->
      <div class="relative bg-gray-100 aspect-square overflow-hidden">
        <img
          src="../assets/tas.png"
          alt="Product"
          class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
        />
      
        <!-- Rating Badge -->
        <div class="absolute top-3 right-3 bg-gray-500 text-white px-3 py-1 rounded-full text-sm font-semibold flex items-center gap-1">
          <span>★</span>
          <span>4.2</span>
        </div>
      </div>

      <!-- Product Info Container -->
      <div class="bg-slate-400 px-4 pt-4 pb-4">
        <!-- Product Title -->
        <h3 class="text-white font-bold text-sm mb-3 line-clamp-2 leading-tight">
          TAS RANSEL PRIA DISTRO<br />POLOS TAS PRIA Tas Pun...
        </h3>

        <!-- Price and Button Section -->
        <div class="flex items-center justify-between">
          <!-- Price -->
          <div class="text-white">
            <p class="text-sm font-semibold">Rp. 229.000</p>
          </div>

          <!-- Buy Button -->
          <button class="bg-yellow-100 hover:bg-yellow-200 text-gray-800 font-bold px-6 py-2 rounded-full transition-colors duration-300">
            Beli
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
.line-clamp-2 {
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
}
</style>
