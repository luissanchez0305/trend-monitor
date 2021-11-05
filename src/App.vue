<template>
  <!--<img alt="Vue logo" src="./assets/logo.png">-->
  <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <Charts msg="Trading Chart in VueJS" />
</template>

<script>
import Charts from './components/Charts.vue'

export default {
  name: 'App',
  components: {
    Charts,
  }
}
</script>

<style>
body {
  background-color: aquamarine;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0 auto;
  background-color: white;
}
</style>
