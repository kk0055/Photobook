<template>
  <div id="app">
    <div id="nav">
 <Home msg="Welcome to Your Vue.js App"/>
    </div>
  </div>

</template>

<script>
import Home from './views/Home.vue'
// import { mapActions } from "vuex";

export default {
  name: 'App',
  components: {
    Home
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
