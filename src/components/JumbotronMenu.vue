<template>
    <div class="jumbotron-menu">
        <div class="menu">
         <ul>
            <li>
                <a href="#">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>   
                </a>
                
            </li>
            <li>
                <a href="#">
                 <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>    
                </a>
               
            </li>
            <li>
                <a href="#">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>    
                </a>
                
            </li>
            <li>
                <a href="#">
                <img class="locator" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>   
                </a>

            </li>
            <li>
                <a href="#">
                <img class="svg" src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>   
                </a>
                
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
    // position: relative;
    // z-index:1;
    background-color: rgb(11, 130, 250);

    .menu{

        width: 65%;
        margin: 0 auto;
        padding: 25px 0 ; 
    }

     ul{
        padding:10px 0px;
        display: flex;
        align-items: center;
        
        

        a{
            
            color:white;
            display: flex;
            justify-content: center;
            align-items: center;
        }
   
        li{ 

        
         
        .locator{
            width: 15%;
         }


        img{

        width: 20%;
         
        }

        .svg{
            width: 14%;
            }

        span{
            
            padding:0px 10px;
           
           font-size: 0.5rem; 
        }
       }
      } 
  }

</style>