<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <FirstTitle msg="Welcome to Your Vue.js App"/>  
    <FirstHero/>     
  </div>
</template>

<script>
import FirstTitle from './components/FirstTitle.vue';
import FirstHero from './components/FirstHero.vue';


export default {
  name: 'App',
  components: {
    FirstTitle,   
    FirstHero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
