<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Home/>
</template>

<script>
import Home from './components/Home/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>




<style>
*{
    background-color: #2c3e50;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;

  margin: 40px;
}

img {
  height: 40vmin;
  pointer-events: none;
}
</style>
