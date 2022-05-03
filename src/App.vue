<template>
  <div id="app">
    <SiteHeader/>
    <div class="content">
      <ContentComp/>
    </div>
    <div class="CompHero">
      <HeroComp/>
    </div>
    
  </div>
</template>

<script>

import SiteHeader from '@/components/HeaderComp.vue'
import ContentComp from '@/components/ContentComponent.vue'
import HeroComp from '@/components/HeroComponent.vue'


export default {
  name: 'App',
  components: {
    SiteHeader,
    ContentComp,
    HeroComp,
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
</style>
