<template>


  <div class="app">
     <div class ="head"> 

     <myHeader content="HEADER"/>
  </div>

    <img alt="Vue logo" src="./assets/logo.png">
    <myBody msg="BODY"/>

  


  <div class="bottom">
    <myFooter footer="FOOTER"/>

  </div>

  </div>





</template>

<script>
import myBody from './components/Body.vue'
import myHeader from './components/Header.vue'
import myFooter from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    myFooter,
    myBody,
    myHeader
  }
}
</script>

<style>
.app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
