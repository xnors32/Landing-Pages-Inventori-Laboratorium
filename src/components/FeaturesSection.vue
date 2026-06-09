<template>
  <section id="features" class="py-2xl px-margin-mobile md:px-margin-desktop bg-white">
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
          <div class="w-12 h-12 rounded-lg bg-primary/10 flex items-center justify-center mb-lg">
            <span class="material-symbols-outlined text-primary fill">inventory_2</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm text-primary mb-sm">Manajemen Inventaris</h3>
          <p class="text-on-surface-variant text-body-sm flex-grow">
            Kelola data inventaris laboratorium secara komprehensif, termasuk, tarik, edit, dan hapus dengan antarmuka yang intuitif.
          </p>
        </div>

        <!-- Feature 2 -->
        <div class="glass-card rounded-2xl p-lg flex flex-col">
          <div class="w-12 h-12 rounded-lg bg-secondary/10 flex items-center justify-center mb-lg">
            <span class="material-symbols-outlined text-secondary fill">lock</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm text-primary mb-sm">Keamanan JWT</h3>
          <p class="text-on-surface-variant text-body-sm flex-grow">
            Sistem autentikasi token berbasis JWT Aman. Akses spesifik yang granular untuk Admin, Laboran, dan Mahasiswa.
          </p>
        </div>

        <!-- Feature 3 -->
        <div class="glass-card rounded-2xl p-lg flex flex-col">
          <div class="w-12 h-12 rounded-lg bg-green-100 flex items-center justify-center mb-lg">
            <span class="material-symbols-outlined text-green-600 fill">leaderboard</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm text-primary mb-sm">Pelaporan & Analitik</h3>
          <p class="text-on-surface-variant text-body-sm flex-grow">
            Akses laporan real-time dan data palet dengan visualisasi yang menarik untuk keputusan bisnis yang lebih baik.
          </p>
        </div>

        <!-- Feature 4 -->
        <div class="glass-card rounded-2xl p-lg flex flex-col">
          <div class="w-12 h-12 rounded-lg bg-purple-100 flex items-center justify-center mb-lg">
            <span class="material-symbols-outlined text-purple-600 fill">settings</span>
          </div>
          <h3 class="font-headline-sm text-headline-sm text-primary mb-sm">Konfigurasi Fleksibel</h3>
          <p class="text-on-surface-variant text-body-sm flex-grow">
            Dokumentasi lengkap dan API yang terdokumentasi untuk integrasi ke sistem lain atau kustomisasi lebih lanjut.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>
