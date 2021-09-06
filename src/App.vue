<template>
  <div id="app">
    <div>
      <Header/>
      <router-view/>
      <Footer/>
    </div>
    
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: "app",
  components:{
    Footer,
    Header
  }
}
</script>

<style>
#app {
  font-family: "Trirong", serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  padding-top: 3em;
}

</style>
