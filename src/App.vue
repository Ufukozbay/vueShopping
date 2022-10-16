<template>
  <div id="app">
    <Navbar />
    <Hero />
    <!-- <Footer/> -->
  </div>
</template>

<script>
import Navbar from './components/common/navbar/navbar.vue'
import Hero from './components/common/hero.vue'
// import Footer from '@/components/common/footer/footer.vue'
export default{
  name: "app",
  components: {Hero , Navbar },
  //  Footer
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
