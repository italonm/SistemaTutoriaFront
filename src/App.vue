<template>
  <div id="app" >
    <Login></Login>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import Login from './components/Login.vue'
import VueMaterial from 'vue-material'
import 'vue-material/dist/vue-material.min.css'
import Vue from 'vue'

Vue.use(VueMaterial)

export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style scoped>
#app {
  /* background-image: url('https://vuejs.org/images/logo.png'); */
  background-image: url("./assets/tutoria.png");
  /* background-size: 100%; */
  height: 100%;
  background-size: cover;

  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
