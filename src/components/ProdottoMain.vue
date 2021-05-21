<template>
  
  <div>
    <img :src="serie.thumb" :alt="serie.series">
    <h3>{{serie.series}}</h3>
  </div>
</template>

<script>
export default {
  name:'ProdottoMain',
  props:{
    serie: Object
  }
}
</script>

<style lang="scss" scoped>
  div{
    padding-top: 80px ;
    flex-basis: calc(100%/6);
    h3{
      width: 100%;
      color: white;
    }
  }
</style>