<template>
    <div class="container">
        <nav>
            <img src="../assets/img/dc-logo.png" alt="">
            <ul>
                <li>
                    <a href="">characters</a>
                    <a href="">comics</a>
                    <a href="">movies</a>
                    <a href="">tv</a>
                    <a href="">games</a>
                    <a href="">collectibiles</a>
                    <a href="">videos</a>
                    <a href="">fans</a>
                    <a href="">news</a>
                    <a href="">shop</a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name:'SiteHeader'
}
</script>


<style lang="scss" scoped>
li{
    list-style: none;
    margin: 0 0.5rem;
}

.container{
    display: flex;
    width: 80%;
    margin: 0 auto;
    justify-content: space-between;

}

a {
    text-transform: uppercase;
    text-decoration: none;
    color: black;
    font-weight: 600;
    padding: 3rem;
    
}

a:hover{
    border-bottom: 4px solid #3382F9;
    color: #3382F9;
}


ul{
    display: flex;
    align-items: center;
}
</style>