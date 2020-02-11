<template>
  <div id="app">
   
	<newPage1></newPage1>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import newPage1 from './components/newPage1.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld,
	newPage1
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
  /* margin-top: 60px; */
}
</style>
