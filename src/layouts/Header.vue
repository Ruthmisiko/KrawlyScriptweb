<script setup>
import { ref } from 'vue';

const mobileNav = ref(false);

const toggleMobileNav = () => {
  mobileNav.value = !mobileNav.value;
};
</script>

<template>
  <!-- Navbar Start -->
  <div class="fixed top-0 left-0 w-full z-50 bg-[#071512]/90 backdrop-blur border-b border-green-900">
    <div class="container mx-auto px-6">
      <header class="flex justify-between py-4 items-center">
        <!-- Logo -->
        <h1 class="text-2xl font-bold text-green-400 tracking-wide">
          Krawly Script Agency
        </h1>

        <!-- Menu -->
        <nav class="flex items-center">
          <!-- Mobile Toggle -->
          <button @click="toggleMobileNav" type="button" class="md:hidden text-green-300 focus:outline-none">
            <svg viewBox="0 0 24 24" class="h-7 w-7 fill-current">
              <path fill-rule="evenodd"
                d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2z" />
            </svg>
          </button>

          <!-- Desktop Menu -->
          <ul class="hidden md:flex gap-10 text-sm font-semibold tracking-widest uppercase text-green-200">
            <li><a href="#home" class="hover:text-green-400 transition">Home</a></li>
            <li><a href="#about" class="hover:text-green-400 transition">About</a></li>
            <li><a href="#services" class="hover:text-green-400 transition">Services</a></li>
            <li><a href="#projects" class="hover:text-green-400 transition">Projects</a></li>
            <li>
              <a href="#contact" class="px-5 py-2 bg-green-700 hover:bg-green-600 rounded-md text-white transition">
                Contact
              </a>
            </li>
          </ul>
        </nav>
      </header>
    </div>

    <!-- Mobile Menu -->
    <div v-show="mobileNav" class="md:hidden">
      <div class="absolute top-0 left-0 w-full h-screen bg-[#071512] px-6 py-8 z-50">
        <div class="flex justify-between items-center mb-10">
          <h1 class="text-xl font-bold text-green-400">Krawly Script Agency</h1>
          <button @click="toggleMobileNav" class="text-green-300">
            ✕
          </button>
        </div>

        <ul class="flex flex-col gap-6 uppercase text-green-200 tracking-widest text-sm">
          <li><a @click="toggleMobileNav" href="#home" class="hover:text-green-400">Home</a></li>
          <li><a @click="toggleMobileNav" href="#about" class="hover:text-green-400">About</a></li>
          <li><a @click="toggleMobileNav" href="#services" class="hover:text-green-400">Services</a></li>
          <li><a @click="toggleMobileNav" href="#projects" class="hover:text-green-400">Projects</a></li>
          <li>
            <a @click="toggleMobileNav" href="#contact" class="bg-green-700 hover:bg-green-600 px-5 py-2 rounded text-white inline-block">
              Contact
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
  <!-- Navbar End -->
</template>
