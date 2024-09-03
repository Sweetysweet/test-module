<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <!-- synchronize the submodule
   git submodule update --remote --merge --recursive -->
   <My-Counter />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyCounter from '@sample-proj/counter/src/components/MyCounter.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    MyCounter
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
