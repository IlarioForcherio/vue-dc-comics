<template>
    <div class="jumbotron">
        <div class="top">
          <h2> --> content -->  </h2>
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
   
}


.top{
    display: flex;
    align-items: center;
    color:white;
    width: 80%;
    margin: 0 auto;
    
    
}



.bottom li{
     display:inline;
     margin: 0 60px;
}

</style>