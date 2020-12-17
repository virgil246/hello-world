<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Torrent title="123"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Torrent from './components/Torrent'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Torrent
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
