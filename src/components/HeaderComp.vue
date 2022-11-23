<template>
    <div>
     <nav>
        <div><img src="../assets/img/dc-logo.png" alt="dc-logo"></div>
        <div>
            <ul>
                <li> <a href="#">CHARACTERS</a></li>
                <li> <a href="#">COMICS</a></li>
                <li> <a href="#">MOVIES</a></li>
                <li> <a href="#">TV</a></li>
                <li> <a href="#">GAMES</a></li>
                <li> <a href="#">COLLECTIBLES</a></li>
                <li> <a href="#">VIDEOS</a></li>
                <li> <a href="#">FANS</a></li>
                <li> <a href="#">NEWS</a></li>
                <li> <a href="#">SHOP</a></li>
            </ul>
        </div>
     </nav>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

nav{
    padding: 10px 0;
    width: 70%;
    margin: 30px auto;
    display:flex;
    align-items: center;
    justify-content: space-between;

    
    img{
        width: 60%; 
    }
    
    li{
     margin: 0 10px;
     display: inline; 
    }

    a{
        font-size: 0.6rem;
        font-weight: bold;
        padding-bottom:20px;

        &:hover{
            color:rgb(11, 130, 250);
            border-bottom:4px solid rgb(11, 130, 250);
        }

    }
}


</style>