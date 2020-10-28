<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logos.png">
    <HelloWorld msg="Welcome to Vin's Care"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
  margin-top: 50px;
}

img{
  margin : 75px 0 25px;
  width: 300px;
}
</style>
