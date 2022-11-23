<template>
    <div>
        <div class="footer">
            <div>
                <h6>SING UP NOW!</h6>
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
    padding: 32px;
    width: 80%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    color:white;
    
}

h6{
    border: 3px solid rgb(20, 110, 199);
    padding: 5px;
}
h5{
    color:rgb(20, 110, 199);
}

.follow{
    display:flex;
    align-items: center;
}
ul{
    display: flex;
}


</style>