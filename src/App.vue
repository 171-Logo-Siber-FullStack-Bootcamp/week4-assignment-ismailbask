<template>
  <SideBar/>  
  <TopBar/>
  <MainTemplete/>
  
</template>

<script>
import MainTemplete from './components/MainTemplete.vue'
import SideBar from './components/SideBar.vue'
import TopBar from './components/TopBar'





export default {
  name: 'App',
  components: {
    MainTemplete,
    SideBar,
    TopBar,


  }
}
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
