<template>
  <div>
    <router-view />

    <Footer />
    <Menu />
  </div>
</template>

<script>
import Footer from './components/footer.vue';
import Menu from "./components/MenuVal.vue";


export default {
  name: 'App',
  components: {
    Footer,
    Menu
  }
}
</script>

<style>

</style>

