<template>
  
  <top-header />
  <router-view></router-view>
  <bottom-footer />
</template>

<script>
import header from './components/header.vue'
import footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
    'top-header':header,
    'bottom-footer':footer,
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
  margin-top: 60px;
}
</style>
