<script setup>
import Navbar from './components/NavbarComponent.vue'
</script>

<template>
  <div class="flex flex-col min-h-screen bg-sky-100">
<Navbar />

 <main class="flex-1 container mx-auto px-4 py-6">
<router-view />
</main>

<footer class="bg-sky-800 text-white py-6 px-8">
<div class="flex flex-col md:flex-row justify-between items-start md:items-center">
  <div class="mb-4 md:mb-0">
      <h4 class="font-semibold text-lg">Contato</h4>
      <p>R. Cides Aprigio Ferreira, 135</p>
      <p>Marília/SP - Brasil</p>
</div>
  <div>
  <h4 class="font-semibold text-lg">Redes Sociais</h4>
  <ul class="space-y-1">
    <li><a href="#">Facebook </a></li>
    <li><a href="#">Instagram </a></li>
    <li><a href="#">Linkedin </a></li>
    </ul>
</div>
</div>
</footer>
</div>
</template>
