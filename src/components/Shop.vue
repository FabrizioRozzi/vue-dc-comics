<template>
  <div class="full">
    <div class="container-80">
      <ul>
        <li
          v-for="(link, index) in links" :key="index"
        >
          <img :src="link.src" :alt="link.text">
          <h5>{{link.text}}</h5>
        </li>
      </ul>
    </div>
  </div>

</template>

<script>
export default {
  name:"Shop",
  data(){
    return{
      links:[
        {
          src:require("@/assets/img/buy-comics-digital-comics.png"),
          text:"DIGITAL COMICS"
        },
        {
          src:require("@/assets/img/buy-comics-merchandise.png"),
          text:"DC MERCHANDISE"
        },
        {
          src:require("@/assets/img/buy-comics-shop-locator.png"),
          text:"SUBSCRIPTION"
        },
        {
          src:require("@/assets/img/buy-comics-subscriptions.png"),
          text:"COMIC SHOP LOCATOR"
        },
        {
          src:require("@/assets/img/buy-dc-power-visa.svg"),
          text:"DC POWER VISA"
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

  .full{
    width: 100%;
    height: 200px;
    background-color: blue;
    ul{
      display: flex;
      justify-content: space-between;
      padding: 60px;
      li{
        display: flex;
        align-items: center;
        img{
          height: 80px;
          padding-right: 10px;
        }
        h5{
          color: white;
        }
      } 
    }
  }

</style>