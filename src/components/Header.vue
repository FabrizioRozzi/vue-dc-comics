<template>
  <div class="container-80">
    <img src="../assets/img/dc-logo.png" alt="logo">
    
    <nav>
      <ul>
        <li v-for="(link, index) in links" :key="index">
          <a 
            :href="link.url">{{link.text}}</a>
        </li>
      </ul>
    </nav>
    
  </div>
</template>
<script>
export default {
  name:'Header.vue',
  data(){
    return{
      links: [
        {
          text:'characters',
          url:'#',
          current: false
        },
        {
          text:'comics',
          url:'#',
          current: false
        },
        {
          text:'movies',
          url:'#',
          current: false
        },
        {
          text:'tv',
          url:'#',
          current: false
        },
        {
          text:'games',
          url:'#',
          current: false
        },
        {
          text:'collectibles',
          url:'#',
          current: false
        },
        {
          text:'videos',
          url:'#',
          current: false
        },
        {
          text:'fans',
          url:'#',
          current: false
        },
        {
          text:'news',
          url:'#',
          current: false
        },
        {
          text:'shop',
          url:'#',
          current: false
        },
      ]
    }
  }
}
</script>
<style lang="scss" scoped>

  div{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 100px;
    
    li{
      display: inline;
      padding: 0 10px;
    }

    a{
      padding-bottom: 38px;
      text-transform: uppercase;
      color: black;
    }

  }

  img{
    height: 80px;
  }

</style> 

