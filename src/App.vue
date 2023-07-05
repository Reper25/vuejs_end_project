<template>
  <Navbar/>
  <router-view/>
  <footercomp/>
</template>

<script>
import Navbar from '@/components/NavbarComp.vue';
import footercomp from '@/components/footer-comp.vue';
export default {
  components: {
    Navbar, 
    footercomp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
