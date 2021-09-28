<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <bottone_prova />
  </div>
</template>



<script>
  import bottone_prova from './components/bottone_prova.vue'

  export default {
    name: 'App',
    components: {
      bottone_prova
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