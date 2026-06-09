<template>
  <header
    class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-margin-mobile md:px-margin-desktop h-20 max-w-full bg-surface/70 backdrop-blur-md border-b border-outline-variant/30 shadow-sm transition-all duration-300"
    :class="{ 'h-16 shadow-md': isScrolled }"
  >
    <!-- Logo -->
    <div class="flex items-center gap-sm">
      <span class="material-symbols-outlined text-primary fill">science</span>
      <span class="text-headline-sm font-headline-sm font-bold text-primary">Sistem Inventaris Lab</span>
    </div>

    <!-- Navigation -->
    <nav class="hidden md:flex gap-lg items-center">
      <a
        href="#features"
        class="text-on-surface-variant hover:text-primary transition-colors font-label-md text-label-md uppercase"
      >
        Features
      </a>
      <a
        href="#architecture"
        class="text-on-surface-variant hover:text-primary transition-colors font-label-md text-label-md uppercase"
      >
        Architecture
      </a>
      <a
        href="#tech"
        class="text-on-surface-variant hover:text-primary transition-colors font-label-md text-label-md uppercase"
      >
        Technology
      </a>
    </nav>

    <!-- CTA Button -->
    <div class="flex items-center gap-md">
      <button class="btn-primary">
        Get Started
      </button>
    </div>
  </header>
</template>

<script setup lang="ts">
import { ref, onMounted, onUnmounted } from 'vue'

const isScrolled = ref(false)

const handleScroll = () => {
  isScrolled.value = window.scrollY > 50
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>
