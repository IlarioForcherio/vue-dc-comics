<template>
    <div class="jumbotron-menu">
        <div class="menu">
         <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>ciao</span>
            </li>
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>ciao</span>
            </li>
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>ciao</span>
            </li>
            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>ciao</span>
            </li>
            <li>
                <img class="svg" src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>ciao</span>
            </li>
        </ul>   
        </div>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>


.jumbotron-menu{
    display: flex;
    justify-content: space-around;
    text-align: left;
    background-color: rgb(11, 130, 250);
}

ul{
    display: flex;
    justify-content: space-around;
   
}

.menu li{ 

    width: 80%;
    margin: 0 auto;
    color: white;
    display: flex;
    align-items: center;
   padding: 0 15px;
}
li img{
    width: 20%;
}
.svg{
    width: 15%;
}


</style>