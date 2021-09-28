<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <bottone_prova/>
    <titolo/>
  </div>
</template>



<script>
  import bottone_prova from './components/bottone_prova.vue'
  import titolo from './components/titolo.vue'

  export default {
    name: 'App',
    components: {
      bottone_prova,
      titolo
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