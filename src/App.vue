
<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
    
  }
   
}


</script>
<template>
  <img alt="Vue logo" src="./assets/logocj.jpg" width="300">
  <HelloWorld msg="BIENVENIDO A CREACIONES JUDITH"/>

  <h1>{{ message }}</h1>

  <!--
    Bind to a method/function.
    The @click syntax is short for v-on:click.
  -->
  <button @click="reverseMessage">Reverse Message</button>

  <!-- Can also be an inline expression statement -->
  <button @click="message += '!'">Append "!"</button>
 
</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
button, a {
  display: block;
  margin-bottom: 1em;
}
</style>
