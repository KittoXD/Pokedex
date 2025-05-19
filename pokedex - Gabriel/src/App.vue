<template>
  <div class="bg-gray-100 min-h-screen flex flex-col">
    <Navbar />
    <div class="main container mx-auto px-4 py-6 flex-grow">
      <router-view />
    </div>
    <FooterComponent />
  </div>
</template>

<script setup>
import Navbar from './components/NavbarComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
</script>