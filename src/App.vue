<template>
  <div id="app">
    <img id="rokuPNG" alt="Vue logo" src="./assets/roku.png">
    <HelloWorld msg="Welcome, Jae"/>


  </div>

  

  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}


</script>

<style>
body{
  background-color: #6D3998;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: #eeeeee;
  padding: 3%;
  
}
#rokuPNG{
  width: 20%
}

</style>
