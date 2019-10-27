<template>
  <div id="app">
    <h2>Wattage Converter</h2>
    <Converter></Converter>
  </div>
</template>

<script>
import Converter from './components/Converter.vue'

export default {
  name: 'app',
  components: {
    Converter
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
