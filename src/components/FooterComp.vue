<template>
    <div>
        <div class="footer">
            <div>
                <h6><a href="#">SING UP NOW!</a></h6>
            </div>
            <div class="follow">
                <h5>FOLLOW US</h5>
                <ul>
                    <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                    <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                    <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                    <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                    <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

.footer{
   
    padding: 10px;
    width: 70%;
    margin: 0 auto;
    
    display: flex;
    align-items: center;
    justify-content: space-between;
    color:white;


    h6{
        
        border: 3px solid rgb(20, 110, 199);
        padding: 10px;

        a{
            color: white;
        }
    }

    .follow{
    display:flex;
    align-items: center;

      h5{
        padding-right:20px;
        color:rgb(16, 125, 250);
     }

     ul{
     display: flex;

     li{
        padding:0 0 ;
     }
     img{
        width: 60%;
     }
     }

    }

}
</style>