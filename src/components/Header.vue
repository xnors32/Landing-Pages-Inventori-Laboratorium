<template>
  <header
    class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-margin-mobile md:px-margin-desktop h-20 max-w-full bg-surface/70 dark:bg-[#070e1c]/70 backdrop-blur-md border-b border-outline-variant/30 dark:border-white/10 shadow-sm transition-all duration-300"
    :class="{ 'h-16 shadow-md': isScrolled }"
  >
    <!-- Logo -->
    <div class="flex items-center gap-sm">
      <span class="material-symbols-outlined text-primary dark:text-secondary-container fill">science</span>
      <span class="text-headline-sm font-headline-sm font-bold text-primary dark:text-white">Sistem Inventaris Lab</span>
    </div>

    <!-- Navigation -->
    <nav class="hidden md:flex gap-lg items-center">
      <a
        href="#features"
        class="text-on-surface-variant dark:text-primary-fixed-dim hover:text-primary dark:hover:text-secondary transition-colors font-label-md text-label-md uppercase"
      >
        Features
      </a>
      <a
        href="#architecture"
        class="text-on-surface-variant dark:text-primary-fixed-dim hover:text-primary dark:hover:text-secondary transition-colors font-label-md text-label-md uppercase"
      >
        Architecture
      </a>
      <a
        href="#tech"
        class="text-on-surface-variant dark:text-primary-fixed-dim hover:text-primary dark:hover:text-secondary transition-colors font-label-md text-label-md uppercase"
      >
        Technology
      </a>
      <a
        href="https://github.com/xnors32/Full-App-FE-BE"
        target="_blank"
        class="text-on-surface-variant dark:text-primary-fixed-dim hover:text-primary dark:hover:text-secondary transition-colors font-label-md text-label-md uppercase"
      >
        Docs
      </a>
      <a
        href="https://frontend-baru.vercel.app/login"
        target="_blank"
        class="text-on-surface-variant dark:text-primary-fixed-dim hover:text-primary dark:hover:text-secondary transition-colors font-label-md text-label-md uppercase"
      >
        Web App
      </a>
    </nav>

    <!-- Theme Toggle & Login -->
    <div class="flex items-center gap-md">
      <ThemeToggle />
      <a
        href="https://frontend-baru.vercel.app/login"
        target="_blank"
        class="btn-primary flex items-center gap-sm"
      >
        <span>Login</span>
        <span class="material-symbols-outlined text-sm">login</span>
      </a>
    </div>
  </header>
</template>

<script setup lang="ts">
import { ref, onMounted, onUnmounted } from 'vue'
import ThemeToggle from './ThemeToggle.vue'

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
