<template>
  <div id="app">
    <Header />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
}
</script>

<style lang="scss">
  .container-80{
    width: 80%;
    margin: 0 auto;
  }

  .active{
    color: blue;
    border-bottom: 5px solid blue;
  }
</style>
