<template>
    <div class="container">
        <div class="">
            <button class="btn">SIGN UP NOW!</button>
        </div>
        <div class="follow">
            <h4>FOLLOW US</h4>
       
            <div class="">
                <img src="../assets/img/footer-facebook.png" alt="">
            </div>
            <div class="">
                <img src="../assets/img/footer-twitter.png" alt="">
            </div>
            <div class="">
                <img src="../assets/img/footer-youtube.png" alt="">
            </div>
            <div class="">
                <img src="../assets/img/footer-pinterest.png" alt="">
            </div>
            <div class="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name:'SiteFooter'
}
</script>

<style lang="scss" scoped>
.container{
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 40px 0;
}

.btn{
    border-color: #0282F9;
    background-color: #303030;
    color: white;
    padding: 15px;
}

h4{
    color: #0282F9;
}

.follow{
    display: flex;
    align-items: center;
}

.follow div{
    margin: 0 10px;
}
</style>