<template>
    <div class="jumbotron">
        <div class="top">
          <h2> --> Content goes here -->  </h2>
        </div>
         <JumbotronMenu id="JumbotronMenu"  />
    </div>
   
</template>

<script>
import JumbotronMenu from '../components/JumbotronMenu.vue'
 
 export default {
  name: 'JumbotronComp',
  components: {
    JumbotronMenu,
  }
}
</script>

<style lang="scss" scoped>

.jumbotron{
    
   background-color: black;

  .top{
    display: flex;
    align-items: center;
    color:white;
    width: 70%;
    margin: 25px auto;
    
    h2{
        font-size: 1.3rem;
    }
} 
}



</style>