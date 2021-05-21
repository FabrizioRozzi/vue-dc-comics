<template>
  <div>
    <div class="container-80">
      <ul>
        <li
          v-for="(link, index) in links" :key="index"
        >
          <img :src="link.src" :alt="link.text">
          <h3>{{link.text}}</h3>
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
          src:"@/assets/img/buy-comics-digital-comics.png",
          text:"DIGITAL COMICS"
        },
        {
          src:"@/assets/img/buy-comics-merchandise.png",
          text:"DC MERCHANDISE"
        },
        {
          src:"@/assets/img/buy-comics-shop-locator.png",
          text:"SUBSCRIPTION"
        },
        {
          src:"@/assets/img/buy-comics-subscriptions.png",
          text:"COMIC SHOP LOCATOR"
        },
        {
          src:"@/assets/img/buy-dc-power-visa.svg",
          text:"DC POWER VISA"
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

  div{
    width: 100%;
    background-color: blue;
    .container-80{

    }
  }

</style>