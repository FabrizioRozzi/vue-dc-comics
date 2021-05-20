<template>
  <div class="container-80">
    <img src="../assets/img/dc-logo.png" alt="logo">
    
    <nav>
      <ul>
        <li>
          <a href="#">characters</a>
        </li>
        <li>
          <a class="active" href="#">comics</a>
        </li>
        <li>
          <a href="#">movies</a>
        </li>
        <li>
          <a href="#">tv</a>
        </li>
        <li>
          <a href="#">games</a>
        </li>
        <li>
          <a href="#">collectibles</a>
        </li>
        <li>
          <a href="#">videos</a>
        </li>
        <li>
          <a href="#">fans</a>
        </li>
        <li>
          <a href="#">news</a>
        </li>
        <li>
          <a href="#">shop</a>
        </li>
      </ul>
    </nav>
    
  </div>
</template>
<script>
export default {
  name:'Header.vue'
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

</style> 

