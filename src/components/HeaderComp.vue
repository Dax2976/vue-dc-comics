<template>
    <div class="container">
         <img src="../assets/img/dc-logo.png" alt="" class="logo">
         <div class="container">
             <nav>
                <ul>
                    <li :key="index" v-for="(elm, index) in navlist">
                        <a :href="elm.ref">{{elm.name}}</a>
                    </li>
                </ul>
            </nav>
         </div>
          
       
    </div>
</template>

<script>
export default {
    name:'SiteHeader',
    data:function(){
        return{
            navlist:[
                {
                    'name': 'character',
                    'ref': '/character',
                },
                 {
                    'name': 'comics',
                    'ref': '/comics' ,
                },
                 {
                    'name': 'movies' ,
                    'ref': '/movies',
                },
                 {
                    'name': 'tv',
                    'ref': '/tv',
                },
                 {
                    'name': 'games',
                    'ref': '/games',
                },
                {
                    'name': 'collectibiles',
                    'ref': '/collectibiles',
                },
                 {
                    'name': 'videos' ,
                    'ref': '/videos',
                },
                 {
                    'name': 'fans',
                    'ref': '/fans',
                },
                 {
                    'name': 'news',
                    'ref': '/news',
                },
                 {
                    'name':'shop' ,
                    'ref': '/shop',
                },
            ]
        }
    }
}
</script>


<style lang="scss" scoped>
.logo{
   justify-content: center;
   padding: 1rem;
}
nav{
    padding: 3rem;
}
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
    padding: 62px 50px;
    margin: -10px;
    
}

a:hover{
    border-bottom: 6px solid #3382F9;
    color: #3382F9;
}


ul{
    display: flex;
    align-items: center;
}
</style>