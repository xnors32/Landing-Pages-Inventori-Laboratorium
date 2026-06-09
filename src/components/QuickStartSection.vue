<template>
  <section class="py-2xl bg-surface-container-low px-margin-mobile md:px-margin-desktop">
    <div class="max-w-4xl mx-auto">
      <!-- Section Header -->
      <div class="text-center mb-xl">
        <h2 class="section-title mb-sm">Quick Start for Developers</h2>
        <p class="section-subtitle">Jalankan proyek dalam hitungan detik dengan CLI.</p>
      </div>

      <!-- Terminal Block -->
      <div class="terminal-block rounded-2xl overflow-hidden shadow-2xl">
        <!-- Terminal Header -->
        <div class="px-lg py-sm bg-primary/80 border-b border-white/10 flex items-center justify-between">
          <div class="flex gap-2">
            <div class="w-3 h-3 rounded-full bg-red-500"></div>
            <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
            <div class="w-3 h-3 rounded-full bg-green-500"></div>
          </div>
          <span class="text-[10px] font-mono text-on-primary-container uppercase tracking-widest">
            zsh — local — 80x24
          </span>
        </div>

        <!-- Terminal Content -->
        <div class="p-xl font-mono text-sm space-y-md text-white">
          <!-- Comment Line -->
          <div class="flex gap-md">
            <span class="text-secondary opacity-50 select-none">1</span>
            <span><span class="text-green-400"># Start Backend Service</span></span>
          </div>

          <!-- Backend Command -->
          <div class="flex gap-md">
            <span class="text-secondary opacity-50 select-none">2</span>
            <span>mvn spring-boot:run</span>
          </div>

          <!-- Spacer -->
          <div class="flex gap-md pt-md">
            <span class="text-secondary opacity-50 select-none">3</span>
            <span><span class="text-green-400"># Start Frontend Client</span></span>
          </div>

          <!-- Frontend Command -->
          <div class="flex gap-md">
            <span class="text-secondary opacity-50 select-none">4</span>
            <span>npm run dev</span>
          </div>

          <!-- Cursor -->
          <div class="pt-lg flex items-center gap-sm">
            <span class="text-yellow-400">➜</span>
            <span class="text-white animate-pulse">_</span>
          </div>
        </div>
      </div>

      <!-- Additional Info -->
      <div class="mt-lg text-center">
        <p class="text-on-surface-variant text-body-sm">
          Sistem akan berjalan di
          <code class="px-2 py-1 bg-white rounded text-xs font-mono">http://localhost:5173</code>
        </p>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
