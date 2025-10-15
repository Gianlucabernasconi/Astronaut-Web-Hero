<template>
  <!-- Header escritorio -->
  <header class="fixed top-0 left-0 w-full z-30 bg-transparent hidden md:block">
    <nav class="flex justify-center gap-12 py-6">
      <a href="#seccion1" class="font-orbit text-[var(--color-texto)] text-lg opacity-30 transition-all hover:opacity-100 hover:scale-105 duration-400">Sección 1</a>
      <a href="#seccion2" class="font-orbit text-[var(--color-texto)] text-lg opacity-30 transition-all hover:opacity-100 hover:scale-105 duration-400">Sección 2</a>
      <a href="#seccion3" class="font-orbit text-[var(--color-texto)] text-lg opacity-30 transition-all hover:opacity-100 hover:scale-105 duration-400">Sección 3</a>
    </nav>
  </header>

  <!-- Header móvil -->
  <header class="fixed top-4 left-0 w-full z-30 bg-transparent md:hidden">
    <div class="flex justify-center items-center relative py-3 border-b border-[var(--color-texto)]/10">
      <button @click="isOpen = !isOpen" class="absolute left-1/2 -translate-x-1/2 mb-3">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-7 h-7 fill-[var(--color-texto)] opacity-70" viewBox="0 0 24 24">
          <path d="M3 6h18v2H3V6zm0 5h18v2H3v-2zm0 5h18v2H3v-2z"/>
        </svg>
      </button>
    </div>

    <nav v-if="isOpen" class="flex flex-col items-center gap-3 bg-black/70 backdrop-blur-md py-5">
      <a href="#seccion1" class="font-orbit text-[var(--color-texto)] text-lg opacity-70 hover:opacity-100 transition-all">Sección 1</a>
      <a href="#seccion2" class="font-orbit text-[var(--color-texto)] text-lg opacity-70 hover:opacity-100 transition-all">Sección 2</a>
      <a href="#seccion3" class="font-orbit text-[var(--color-texto)] text-lg opacity-70 hover:opacity-100 transition-all">Sección 3</a>
    </nav>
  </header>
</template>

<script setup>
import { ref } from 'vue'
const isOpen = ref(false)
</script>

<style scoped>
.font-orbit {
  font-family: 'Orbit', sans-serif;
}
</style>
