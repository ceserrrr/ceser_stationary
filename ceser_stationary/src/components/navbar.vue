<template>
  <nav class="bg-yellow-50 shadow-md">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <!-- Logo -->
        <div class="shrink-0">
          <img src="../assets/logo.png" alt="CESER Stationery" class="h-12 w-auto" />
        </div>

        <!-- Search Bar -->
        <div class="flex-1 mx-6">
          <div class="relative">
            <input
              type="text"
              placeholder="Cari barang..."
              class="w-100 px-4 py-2 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-gray-400"
            />
            <button class="absolute right-87 top-2.5 text-gray-400 hover:text-gray-600">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
              </svg>
            </button>
          </div>
        </div>

        <!-- Right Side Items -->
        <div class="flex items-center space-x-4">
          <!-- Kategori Dropdown -->
          <div class="relative group">
            <button class="px-4 py-2 rounded-lg border border-gray-300 hover:bg-gray-100 transition flex items-center space-x-2">
              <span>Kategori</span>
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
              </svg>
            </button>
            <!-- Dropdown Menu -->
            <div class="absolute left-0 mt-2 w-48 bg-white rounded-lg shadow-lg opacity-0 group-hover:opacity-100 group-hover:pointer-events-auto pointer-events-none transition-opacity z-10">
              <a href="#" class="block px-4 py-2 text-gray-700 hover:bg-yellow-50">Buku & Tulis</a>
              <a href="#" class="block px-4 py-2 text-gray-700 hover:bg-yellow-50">Alat Kantor</a>
              <a href="#" class="block px-4 py-2 text-gray-700 hover:bg-yellow-50">Sekolah</a>
              <a href="#" class="block px-4 py-2 text-gray-700 hover:bg-yellow-50">Teknologi</a>
            </div>
          </div>

          <!-- Shopping Cart -->
          <button class="relative p-2 text-gray-600 hover:text-yellow-600 transition">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"></path>
            </svg>
            <span class="absolute top-0 right-0 inline-flex items-center justify-center px-2 py-1 text-xs font-bold leading-none text-white transform translate-x-1/2 -translate-y-1/2 bg-red-500 rounded-full">0</span>
          </button>

          <!-- Login & Register Buttons -->
          <button class="px-4 py-2 text-gray-700 hover:text-yellow-600 transition font-medium">
            Masuk
          </button>
          <button class="px-6 py-2 bg-gray-800 text-white rounded-lg hover:bg-gray-700 transition font-medium">
            Daftar
          </button>
        </div>
      </div>
    </div>
  </nav>
</template>

<script setup></script>

<style scoped></style>
