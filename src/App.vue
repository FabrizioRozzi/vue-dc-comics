<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Main />
    <FooterTop />
    <FooterBottom />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'
import Main from './components/Main.vue'
import FooterTop from './components/FooterTop.vue'
import FooterBottom from './components/FooterBottom.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    FooterTop,
    FooterBottom,
    Main
  }
}
</script>

<style lang="scss">
  *{
    font-family: "Greta Sans Medium","Greta Sans Regular",Arial,sans-serif;
  }
  .container-80{
    max-width: 1200px;
    width: 80%;
    margin: 0 auto;
  }
  .container-50{
    width: 50%;
  }

  .active{
    color: blue;
    border-bottom: 5px solid blue;
  }

  li{
    list-style: none;
  }

  a{
    text-decoration: none;
  }
</style>
