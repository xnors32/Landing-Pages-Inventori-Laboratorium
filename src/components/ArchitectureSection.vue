<template>
  <section id="architecture" class="py-2xl px-margin-mobile md:px-margin-desktop bg-primary text-on-primary">
    <div class="max-w-7xl mx-auto">
      <!-- Section Header -->
      <div class="text-center mb-2xl">
        <h2 class="font-headline-lg text-headline-lg text-on-primary mb-sm">Modern 3-Tier Architecture</h2>
        <p class="text-primary-fixed-dim">Dirancang dengan teknologi terkini untuk efisiensi, performa, keamanan, dan skalabilitas tinggi penuh.</p>
      </div>

      <!-- Architecture Grid -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-lg">
        <!-- Frontend Layer -->
        <div class="glass-card-dark rounded-xl p-lg flex flex-col items-center text-center">
          <div class="w-16 h-16 rounded-full bg-secondary/20 flex items-center justify-center mb-lg">
            <span class="material-symbols-outlined text-secondary text-4xl">dashboard</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm mb-sm">Frontend Layer</h3>
          <p class="text-on-primary-container text-sm mb-lg">Responsive, progressive app interface untuk memberikan user pengalaman terbaik.</p>
          <div class="flex flex-wrap justify-center gap-xs">
            <span class="px-3 py-1 bg-white/10 rounded-full text-[10px] font-bold">VUE 3</span>
            <span class="px-3 py-1 bg-white/10 rounded-full text-[10px] font-bold">TAILWIND</span>
            <span class="px-3 py-1 bg-white/10 rounded-full text-[10px] font-bold">VITE</span>
          </div>
        </div>

        <!-- Backend Engine -->
        <div class="glass-card-dark rounded-xl p-lg flex flex-col items-center text-center">
          <div class="w-16 h-16 rounded-full bg-green-500/20 flex items-center justify-center mb-lg">
            <span class="material-symbols-outlined text-green-400 text-4xl">code</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm mb-sm">Backend Engine</h3>
          <p class="text-on-primary-container text-sm mb-lg">Robust business logic dan REST API yang aman dengan security terbaik.</p>
          <div class="flex flex-wrap justify-center gap-xs">
            <span class="px-3 py-1 bg-white/10 rounded-full text-[10px] font-bold">SPRING BOOT</span>
            <span class="px-3 py-1 bg-white/10 rounded-full text-[10px] font-bold">JWT AUTH</span>
          </div>
        </div>

        <!-- Database -->
        <div class="glass-card-dark rounded-xl p-lg flex flex-col items-center text-center">
          <div class="w-16 h-16 rounded-full bg-blue-500/20 flex items-center justify-center mb-lg">
            <span class="material-symbols-outlined text-blue-400 text-4xl">database</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm mb-sm">Data Persistence</h3>
          <p class="text-on-primary-container text-sm mb-lg">Penyimpanan data yang terstruktur dengan integritas referensial yang tinggi.</p>
          <div class="flex flex-wrap justify-center gap-xs">
            <span class="px-3 py-1 bg-white/10 rounded-full text-[10px] font-bold">MARIADB</span>
            <span class="px-3 py-1 bg-white/10 rounded-full text-[10px] font-bold">RDBMS</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
