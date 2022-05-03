<template>
  <div id="app">
    <SiteHeader/>
    <div class="content">
      <ContentComp/>
    </div>
    <div class="CompHero">
      <HeroComp/>
    </div>
    <div class="bgmain">
      <div class="main">
        <MainComp/>
        <div class="logobg"></div>
      </div>
    </div>
    <div class="footer">
      <SiteFooter/>
    </div>
  </div>
</template>

<script>

import SiteHeader from '@/components/HeaderComp.vue'
import ContentComp from '@/components/ContentComponent.vue'
import HeroComp from '@/components/HeroComponent.vue'
import MainComp from '@/components/MainComponent.vue'
import SiteFooter from '@/components/FooterComp.vue'


export default {
  name: 'App',
  components: {
    SiteHeader,
    ContentComp,
    HeroComp,
    SiteFooter,
    MainComp,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.content{
  background-color: black ;
}

.bgmain{
  background-image: url('../src/assets/img/footer-bg.jpg');
  background-position: center;
  background-size: cover;
}

.main{
  display: flex;
  height: 300px;
  width: 80%;
  margin: auto;
}

.logobg{
   background-image: url('../src/assets/img/dc-logo-bg.png');
   height: 100%;
   width: 800px;
   background-size: cover;
   background-repeat: no-repeat;
   background-position: center;
}

.footer{
  background-color:#303030 ;
}
</style>
