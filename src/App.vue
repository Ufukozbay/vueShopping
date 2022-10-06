<template>
  <div id="app">
    <navbar></navbar>
    <hero></hero>
    <items></items>
  </div>
</template>

<script>
import Navbar from './components/common/navbar/navbar.vue'
import Hero from './components/Hero.vue'
import Items from './components/items.vue'
export default{
  components: { Hero, Navbar, Items },
  name: "app"
}
</script>

<style >
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
