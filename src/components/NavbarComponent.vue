<template>
  
<nav class="bg-sky-800 text-white py-4 px-8 flex justify-between items-center">
  <h1 class="text-lg font-bold">Meu Currículo</h1>
  <ul class="flex gap-6">

<li><router-link to="/" class="nav-link">Início</router-link></li>
<li><router-link to="/about" class="nav-link">Sobre</router-link></li>
<li><router-link to="/contact" class="nav-link">Contato</router-link></li>
<li><router-link to="/principal" class="nav-link">Portifólio</router-link></li>
</ul>
</nav>
</template>

<style scoped>
.nav-link {
  position: relative;
  font-style: italic;
  text-decoration: none;
  color: inherit;
  padding-bottom: 2px;
  transition: color 0.3s ease;
}

.nav-link::after {
  content: '';
  position: absolute;
  left: 0;
  bottom: 0;
  height: 2px;
  width: 0%;
  background-color: #3b82f6;
  transition: width 0.3s ease;
}

.nav-link:hover::after,
.nav-link.router-link-exact-active::after {
  width: 100%;
}

.nav-link:hover {
  color: #93c5fd;
}
</style>
