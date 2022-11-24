<template>
    <div>
        <div class="main">
            <div class="list">
                <ul>
                   <h5>DC COMICS</h5>
                   <li><a href="#">Characters</a></li>
                   <li><a href="#">Comics</a></li>
                   <li><a href="#">Movies</a></li>
                   <li><a href="#">TV</a></li>
                   <li><a href="#">Games</a></li>
                   <li><a href="#">Videos</a></li>
                   <li><a href="#">News</a></li>
                    <h5>SHOP</h5>
                   <li><a href="#">Shop DC</a></li>
                   <li><a href="#">Shop DC Collections</a></li>
                </ul>
                <ul>
                 <h5>DC</h5>
                 <li><a href="#">Terms of Use</a></li>
                 <li><a href="#">Privacy (New)</a></li>
                 <li><a href="#">Ad Choises</a></li>
                 <li><a href="#">Advertising</a></li>
                 <li><a href="#">Jobs</a></li>
                 <li><a href="#">Subscriptions</a></li>
                 <li><a href="#">Talent Workshops</a></li>
                 <li><a href="#">CPSC Certificates</a></li>
                 <li><a href="#">Ratings</a></li>
                 <li><a href="#">Shop Help</a></li>
                 <li><a href="#">Contact Us</a></li>
                </ul>
                <ul>
                 <h5>SITES</h5>
                 <li><a href="#">DC</a></li>
                 <li><a href="#">MAD Magazine</a></li>
                 <li><a href="#">DC kids</a></li>
                 <li><a href="#">DC Universe</a></li>
                 <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
           
             <img src="../assets/img/dc-logo-bg.png" alt="">    
            
            
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

.main{
    width: 70%;
    height: 250px;
    margin:0 auto;
    color: white;
    display:flex;
    justify-content: space-between;
   

      img{
      position: relative;
      z-index:0;
      width: 50%;
      object-fit:cover;
    }

    

  .list{
      display:flex;
      padding-top: 20px;

      h5{ 
        padding-bottom:8px;
       color: rgb(255, 255, 255);
      }

      ul{
        padding:0px 10px;

        li{
            line-height: 0.7rem;
        }
      }

      a{
       font-size: 0.5rem;
       color: rgb(149, 149, 149);
      }
   }
   
  
}

</style>