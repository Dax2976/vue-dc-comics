<template>
  <div class="card">
      <div class="ImgComics">
          <img :src="details.thumb" alt="">
      </div>
      <span>
          {{details.series}}
      </span>
  </div>
</template>

<script>
export default {
    name:'ComicsComp',
    props:  ['details']
}
</script>

<style lang="scss" scoped>
    span{
        color: white;
        text-transform: uppercase;
        margin: 12px 0;
        display: inline-block;
        max-width: 220px;
    }

    img{
        width: 100%;
        height: 100%;

    }

    .ImgComics{
        height: 220px;
        width: 190px;
    }

    .card{
        margin-bottom: 50px; 
        width: calc(100% / 12 )*2;
        text-align: left;
    }
</style>