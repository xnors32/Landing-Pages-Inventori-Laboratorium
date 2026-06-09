<template>
  <button
    class="relative w-16 h-8 rounded-full transition-colors duration-300 focus:outline-none"
    :class="isDark ? 'bg-primary' : 'bg-outline-variant'"
    @click="toggleTheme"
    aria-label="Toggle theme"
  >
    <span
      class="absolute top-1 left-1 w-6 h-6 rounded-full flex items-center justify-center transition-transform duration-300 shadow-sm"
      :class="isDark ? 'translate-x-8 bg-primary-container' : 'translate-x-0 bg-white'"
    >
      <span v-if="isDark" class="material-symbols-outlined text-sm fill text-on-primary-container">dark_mode</span>
      <span v-else class="material-symbols-outlined text-sm fill text-primary">light_mode</span>
    </span>
  </button>
</template>

<script setup lang="ts">
import { ref, onMounted } from 'vue'

const isDark = ref(false)

const applyTheme = (dark: boolean) => {
  isDark.value = dark
  if (dark) {
    document.documentElement.classList.add('dark')
  } else {
    document.documentElement.classList.remove('dark')
  }
  localStorage.setItem('theme', dark ? 'dark' : 'light')
}

const toggleTheme = () => {
  applyTheme(!isDark.value)
}

onMounted(() => {
  const saved = localStorage.getItem('theme')
  const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches
  applyTheme(saved ? saved === 'dark' : prefersDark)
})
</script>
