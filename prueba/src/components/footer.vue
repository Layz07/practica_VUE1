<template>
  <footer class="bg-gray-900 text-gray-300 py-6 mt-10">
    <div class="max-w-6xl mx-auto px-4 flex flex-col md:flex-row justify-between items-center">
      
      <!-- Logo / Nombre -->
      <div class="flex items-center space-x-2">
        <img 
          src="https://upload.wikimedia.org/wikipedia/commons/5/5a/Valorant_logo_-_pink_color_version.svg" 
          alt="Valorant Logo" 
          class="w-8 h-8"
        />
        <span class="text-lg font-bold text-white">Valorant Info</span>
      </div>
      
      <!-- Navegación -->
      <div class="flex space-x-6 mt-4 md:mt-0">
        <a href="#" class="hover:text-red-500">Inicio</a>
        <a href="#" class="hover:text-red-500">Agentes</a>
        <a href="#" class="hover:text-red-500">Mapas</a>
        <a href="#" class="hover:text-red-500">Noticias</a>
      </div>
      
      <!-- Redes sociales -->
      <div class="flex space-x-4 mt-4 md:mt-0">
        <a href="#" class="hover:text-red-500">
          <i class="fa-brands fa-twitter"></i>
        </a>
        <a href="#" class="hover:text-red-500">
          <i class="fa-brands fa-youtube"></i>
        </a>
        <a href="#" class="hover:text-red-500">
          <i class="fa-brands fa-twitch"></i>
        </a>
      </div>
    </div>
    
    <!-- Línea inferior -->
    <div class="text-center text-sm text-gray-500 mt-6 border-t border-gray-700 pt-4">
      © 2025 Valorant Info - Página de fans. No oficial de Riot Games.
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterValorant",
};
</script>

<style scoped>

</style>
