<template>
    <div class="container">
        <div class="ContImg">
            <div class="space">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>digital comics</span>
            </div>
            <div class="space">
                 <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>dc merchandise</span>
            </div>
            <div class="space">
                 <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>comic shop locator</span>
            </div>
            <div class="space">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>subscriptions</span>
            </div>
            <div class="space">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>dc power visa</span>
            </div> 
        </div>
    </div>
</template>

<script>
export default {
    name: 'HeroComp'
}
</script>


<style lang="scss" scoped>
.container{
    background-color: #3382F9;
    display: flex;
    justify-content: space-between;
    padding: 4.5rem;
    
}

.space{
    display: flex;
    justify-content: space-between;
    align-items: center;
}


.ContImg{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

span{
    color:white;
    text-transform: uppercase;
    font-size: 14px;
    margin: 10px ;
}
</style>