<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HeaderComp id="header" />
    <JumbotronComp id="JumbotronComp"  />
    <MainComp id="main" />
    <FooterComp id="footer"  />
  </div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import JumbotronComp from './components/JumbotronComp.vue'
import MainComp from './components/MainComp.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    JumbotronComp,
    MainComp,
    FooterComp
  }
}
</script>



<style lang="scss">
a{
  color: black;
  text-decoration: none;
}

li{
  list-style: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}


</style>
