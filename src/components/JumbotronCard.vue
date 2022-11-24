<template>
    <div class="card-cnt">
      <div class="card">
       <img :src="dettagliComics.thumb" alt="">
        <div><h6>{{dettagliComics.series}}</h6></div>
      </div>
    </div>
</template>

<script>
export default {
    name:'JumbotronCard',
    props:{
     dettagliComics: Object
    }
}
</script>

<style lang="scss" scoped>

.card-cnt{
width: calc(100% / 6);   
display: flex;
}

.card{
    padding:10px;
    color: white;
   

    

    img{
        width:100%;
        aspect-ratio: 1/1;
        object-fit:cover;
        object-position:top;
    }


}

</style>