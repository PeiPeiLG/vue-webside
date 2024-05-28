<template>
  <div id="app" >
    <Navbar/>
    <router-view/>
    <Footer/>
  </div>
</template>

<style lang="scss">
  @import "./assets/all";
  
</style>

<script>
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';
  export default {
    components: {
      Navbar,
      Footer,
    },
  };
</script>
