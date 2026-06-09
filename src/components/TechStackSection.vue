<template>
  <section id="tech" class="py-2xl px-margin-mobile md:px-margin-desktop bg-white max-w-7xl mx-auto">
    <!-- Section Header -->
    <div class="flex flex-col md:flex-row justify-between items-end gap-md mb-xl">
      <div>
        <h2 class="section-title mb-sm">Spesifikasi Teknologi</h2>
        <p class="section-subtitle">Detail versi dependency yang digunakan dalam proyek ini.</p>
      </div>
    </div>

    <!-- Tech Stack Table -->
    <div class="overflow-x-auto rounded-2xl border border-outline-variant/30">
      <table class="w-full text-left border-collapse bg-white">
        <thead class="bg-surface-container-low border-b border-outline-variant/30">
          <tr>
            <th class="p-lg font-headline-sm text-primary">Kategori</th>
            <th class="p-lg font-headline-sm text-primary">Teknologi</th>
            <th class="p-lg font-headline-sm text-primary">Versi</th>
            <th class="p-lg font-headline-sm text-primary">Status</th>
          </tr>
        </thead>
        <tbody class="divide-y divide-outline-variant/20">
          <tr v-for="(tech, index) in technologies" :key="index" class="hover:bg-surface-container/20 transition-colors">
            <td class="p-lg font-bold text-primary">{{ tech.category }}</td>
            <td class="p-lg">{{ tech.name }}</td>
            <td class="p-lg">
              <code class="px-2 py-1 bg-surface-container rounded text-xs">{{ tech.version }}</code>
            </td>
            <td class="p-lg">
              <span :class="getStatusBadgeClass(tech.status)" class="status-badge">
                <span class="w-1.5 h-1.5 rounded-full" :class="getStatusDotClass(tech.status)"></span>
                {{ tech.status }}
              </span>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>
</template>

<script setup lang="ts">
interface Technology {
  category: string
  name: string
  version: string
  status: string
}

const technologies: Technology[] = [
  { category: 'Language', name: 'Java', version: '21 LTS', status: 'STABLE' },
  { category: 'Backend Framework', name: 'Spring Boot', version: '3.2.5', status: 'ACTIVE' },
  { category: 'Frontend Framework', name: 'Vue.js', version: '3.5.0', status: 'LATEST' },
  { category: 'Frontend Build Tool', name: 'Vite', version: '5.4.0', status: 'LATEST' },
  { category: 'Styling', name: 'Tailwind CSS', version: '3.4.0', status: 'LATEST' },
  { category: 'Database', name: 'MariaDB', version: '11.x', status: 'STABLE' },
]

const getStatusBadgeClass = (status: string) => {
  switch (status) {
    case 'STABLE':
    case 'ACTIVE':
    case 'LATEST':
      return 'status-badge-success'
    case 'DEPRECATED':
      return 'status-badge-warning'
    case 'UNSUPPORTED':
      return 'status-badge-error'
    default:
      return 'status-badge-success'
  }
}

const getStatusDotClass = (status: string) => {
  switch (status) {
    case 'STABLE':
    case 'ACTIVE':
    case 'LATEST':
      return 'bg-green-500'
    case 'DEPRECATED':
      return 'bg-yellow-500'
    case 'UNSUPPORTED':
      return 'bg-red-500'
    default:
      return 'bg-green-500'
  }
}
</script>
