<template>
  <div class="app">
    <router-view>
      <Home />
    </router-view>
  </div>
  
</template>

<script>
import Home from './views/Home.vue'

export default {
  components: { Home },
  name: 'App'
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
