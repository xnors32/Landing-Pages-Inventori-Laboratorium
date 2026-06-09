<template>
  <section id="features" class="py-2xl px-margin-mobile md:px-margin-desktop bg-white dark:bg-[#0b1329] transition-colors duration-300">
    <div class="max-w-7xl mx-auto">
      <!-- Section Header -->
      <div class="mb-2xl">
        <h2 class="section-title mb-sm">Fitur Utama</h2>
        <div class="w-12 h-1 bg-secondary rounded-full"></div>
      </div>

      <!-- Features Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-lg">
        <!-- Feature 1 -->
        <div class="glass-card rounded-2xl p-lg flex flex-col">
          <div class="w-12 h-12 rounded-lg bg-primary/10 dark:bg-white/10 flex items-center justify-center mb-lg transition-colors">
            <span class="material-symbols-outlined text-primary dark:text-secondary-fixed-dim fill">inventory_2</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm text-primary dark:text-white mb-sm transition-colors">Manajemen Inventaris</h3>
          <p class="text-on-surface-variant dark:text-primary-fixed-dim text-body-sm flex-grow transition-colors">
            Kelola data inventaris laboratorium secara komprehensif, termasuk, tarik, edit, dan hapus dengan antarmuka yang intuitif.
          </p>
        </div>

        <!-- Feature 2 -->
        <div class="glass-card rounded-2xl p-lg flex flex-col">
          <div class="w-12 h-12 rounded-lg bg-secondary/10 dark:bg-secondary/20 flex items-center justify-center mb-lg transition-colors">
            <span class="material-symbols-outlined text-secondary dark:text-secondary-fixed-dim fill">lock</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm text-primary dark:text-white mb-sm transition-colors">Keamanan JWT</h3>
          <p class="text-on-surface-variant dark:text-primary-fixed-dim text-body-sm flex-grow transition-colors">
            Sistem autentikasi token berbasis JWT Aman. Akses spesifik yang granular untuk Admin, Laboran, dan Mahasiswa.
          </p>
        </div>

        <!-- Feature 3 -->
        <div class="glass-card rounded-2xl p-lg flex flex-col">
          <div class="w-12 h-12 rounded-lg bg-green-100 dark:bg-green-950/40 flex items-center justify-center mb-lg transition-colors">
            <span class="material-symbols-outlined text-green-600 dark:text-green-400 fill">leaderboard</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm text-primary dark:text-white mb-sm transition-colors">Pelaporan & Analitik</h3>
          <p class="text-on-surface-variant dark:text-primary-fixed-dim text-body-sm flex-grow transition-colors">
            Akses laporan real-time dan data palet dengan visualisasi yang menarik untuk keputusan bisnis yang lebih baik.
          </p>
        </div>

        <!-- Feature 4 -->
        <div class="glass-card rounded-2xl p-lg flex flex-col">
          <div class="w-12 h-12 rounded-lg bg-purple-100 dark:bg-purple-950/40 flex items-center justify-center mb-lg transition-colors">
            <span class="material-symbols-outlined text-purple-600 dark:text-purple-400 fill">settings</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm text-primary dark:text-white mb-sm transition-colors">Konfigurasi Fleksibel</h3>
          <p class="text-on-surface-variant dark:text-primary-fixed-dim text-body-sm flex-grow transition-colors">
            Dokumentasi lengkap dan API yang terdokumentasi untuk integrasi ke sistem lain atau kustomisasi lebih lanjut.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
