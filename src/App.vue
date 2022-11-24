<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HeaderComp id="HeaderComp" />
    <JumbotronComp id="JumbotronComp"  />
    <MainComp id="MainComp" />
    <FooterComp id="FooterComp"  />
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

*{
  margin: 0;
  padding:0;
  box-sizing: border-box;
}

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
  
  color: #2c3e50;
  
}

#HeaderComp{
  background-color: white;
}



#MainComp{
   background-image: url('../src/assets/img/footer-bg.jpg');
   background-position: center;
   background-repeat: no-repeat;
   background-size: cover;
}

#FooterComp{
  background-color: rgb(48, 48, 48);
}




</style>
