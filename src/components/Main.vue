<template>
<div>
  <div class="container-80">
    <ProdottoMain
      v-for="(prodotto, index) in prodotti" :key="index"
      :serie="prodotto"
    />
  </div>
  
  <button><h3>LOAD MORE</h3></button>

  <shop/>

</div>
</template>

<script>

import prodotti from '@/assets/data/dc-comics.js';
import ProdottoMain from '@/components/ProdottoMain.vue';
import Shop from '@/components/Shop.vue';

export default {
  name: 'Main',

  components:{
    ProdottoMain,
    Shop
  },

  data(){
    return{
      prodotti
    }
  },
  
  mounted(){
    console.log(prodotti);
  }

}

</script>

<style lang="scss" scoped>
  div{
    width: 100%;
    background-color: #1C1C1C;
    text-align: center;
  }
  .container-80{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    
  }

  button{
    margin: 30px 0;
    padding: 0 50px;
    background-color: blue;
    color: white;
    border: none;
  }

</style>