<template>
  <div>
    <!-- Aquí todo el contenido principal de tu aplicación -->
    <router-view />

    <!-- Aquí se llama al componente Footer -->
    <Footer />
  </div>
</template>

<script>
// Importamos el componente que está en src/components/footer.vue
import Footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
    Footer
  }
}
</script>

<style>
/* Tus estilos globales */
</style>

