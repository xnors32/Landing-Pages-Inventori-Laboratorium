<template>
  <div class="w-full">
    <Header />
    <main class="pt-20">
      <HeroSection />
      <FeaturesSection />
      <ArchitectureSection />
      <TechStackSection />
      <QuickStartSection />
    </main>
    <Footer />
  </div>
</template>

<script setup lang="ts">
import Header from './components/Header.vue'
import HeroSection from './components/HeroSection.vue'
import FeaturesSection from './components/FeaturesSection.vue'
import ArchitectureSection from './components/ArchitectureSection.vue'
import TechStackSection from './components/TechStackSection.vue'
import QuickStartSection from './components/QuickStartSection.vue'
import Footer from './components/Footer.vue'
</script>
