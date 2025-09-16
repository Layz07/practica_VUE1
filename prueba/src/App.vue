<template>
  <div>
    <router-view />
    <Menu />
    <ValorantBody />
    <Footer />
  </div>
</template>

<script>
import Footer from './components/footer.vue';
import Menu from "./components/MenuVal.vue";
import ValorantBody from './components/ValorantBody.vue';


export default {
  name: 'App',
  components: {
    Menu,
    ValorantBody,
    Footer,  
  }
}
</script>

<style>

</style>

