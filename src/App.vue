<template>
  <div id="app">
<!--    <img alt="Vue logo" src="./assets/logo.png">-->
<!--    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <index></index>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import index from "./components/office/index";

export default {
  name: 'App',
  components: {
    // HelloWorld,
    index,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  color: #2c3e50;
  /*margin-top: 60px;*/

}
    body{
        margin: 0;
    }
</style>
