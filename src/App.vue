<template>

  <div id="app">
    
<NabBar/>

</div> 
</template>

<script>
import NabBar from '@/components/NabBar.vue'

//<img alt="Vue logo" src="./assets/AdobeStock_291470656a copy.png">
export default {
  name: 'App',
  components: {
   NabBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 10px;
  padding-left: 100px;
  background-color:relative;
 
  max-width: 1900px;
  margin: auto;
  background: rgb(247, 235, 235);
  padding: 10px;

}

body {
  background: rgb(247, 230, 230);
}


</style>
