<template>
  <footer class="w-full py-xl px-margin-mobile md:px-margin-desktop flex flex-col md:flex-row justify-between items-center gap-md bg-primary dark:bg-[#060c18] text-on-primary border-t border-primary-container dark:border-white/10 transition-colors duration-300">
    <!-- Logo Section -->
    <div class="flex items-center gap-sm">
      <span class="material-symbols-outlined text-secondary-fixed-dim fill">science</span>
      <span class="font-headline-sm text-headline-sm text-on-primary">Sistem Inventaris Laboratorium</span>
    </div>

    <!-- Navigation Links -->
    <div class="flex gap-xl">
      <a
        href="https://github.com/xnors32/Full-App-FE-BE"
        target="_blank"
        class="text-primary-fixed-dim hover:text-secondary-fixed transition-colors font-body-sm text-body-sm hover:underline uppercase"
      >
        Dokumentasi
      </a>
      <a
        href="https://frontend-baru.vercel.app/login"
        target="_blank"
        class="text-primary-fixed-dim hover:text-secondary-fixed transition-colors font-body-sm text-body-sm hover:underline uppercase"
      >
        Web App
      </a>
    </div>

    <!-- Copyright -->
    <div class="text-body-sm text-primary-fixed-dim text-center md:text-right">
      <p>© 2024 Sistem Inventaris Laboratorium. All rights reserved.</p>
    </div>
  </footer>
</template>

<script setup lang="ts">
</script>
