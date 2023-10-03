<template>
  <div  id="app">
    <primeiroComponente/>
  </div>
</template>

<script>
import primeiroComponente from './components/primeiroComponente.vue'

export default {
  name: 'App',
  components: {
    primeiroComponente
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
