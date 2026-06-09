<template>
  <section class="relative min-h-[870px] flex items-center justify-center overflow-hidden px-margin-mobile md:px-margin-desktop bg-surface-bright dark:bg-[#070e1c] transition-colors duration-300">
    <div class="relative z-10 max-w-5xl mx-auto text-center">
      <!-- Badge -->
      <div
        class="inline-flex items-center gap-xs px-md py-1 bg-secondary-container/20 text-secondary border border-secondary-container/30 dark:bg-secondary/20 dark:text-secondary-fixed-dim dark:border-secondary/30 rounded-full mb-lg animate-pulse"
      >
        <span class="material-symbols-outlined text-sm fill">verified</span>
        <span class="text-[10px] font-bold tracking-wider uppercase">Production Ready — Last Updated 31 Mei 2024</span>
      </div>

      <!-- Heading -->
      <h1 class="font-headline-xl text-headline-xl text-primary dark:text-white mb-md md:text-6xl leading-tight">
        Manajemen Inventaris Laboratorium <br class="hidden md:block" />
        <span class="text-secondary dark:text-secondary-fixed-dim">Lebih Efisien & Terpadu</span>
      </h1>

      <!-- Subtitle -->
      <p class="text-on-surface-variant dark:text-primary-fixed-dim text-body-md md:text-body-lg max-w-2xl mx-auto mb-lg">
        Solusi full-stack modern dengan Vue 3 dan Spring Boot untuk pengelolaan barang, penyimpanan, dan personel yang presisi.
      </p>

      <!-- CTA Buttons -->
      <div class="flex flex-col md:flex-row gap-md justify-center items-center">
        <a
          href="https://frontend-baru.vercel.app/login"
          target="_blank"
          class="btn-primary flex items-center gap-sm"
        >
          <span>Masuk Aplikasi</span>
          <span class="material-symbols-outlined text-sm">arrow_outward</span>
        </a>
        <a
          href="https://github.com/xnors32/Full-App-FE-BE"
          target="_blank"
          class="btn-secondary flex items-center gap-sm"
        >
          <span class="material-symbols-outlined text-sm">description</span>
          <span>Lihat Dokumentasi</span>
        </a>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
