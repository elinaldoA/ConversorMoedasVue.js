<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" class="text-center">
    <h1 class="text-center">Conversor  de Moedas</h1>

    <div class="linha">
      <Conversor moeda-a="USD" moeda-b="BRL"></Conversor>
      <Conversor moeda-a="BRL" moeda-b="USD"></Conversor>
    </div>
    
  </div>
</template>

<script>
import Conversor from "./components/Conversor";
export default {
  name: 'app',
  components: {
    Conversor
  }
}
</script>

<style>
#app {
  max-width: 900px;
  margin: auto;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
  .linha{
    margin-top: 40px;
    display: flex;
    justify-content: space-around;
  }
</style>
