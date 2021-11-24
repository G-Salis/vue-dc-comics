<template>
  <div id="app">

    <Header/>
    <Main/>
    <Shop/>
    <Footer/>
    <Social/>

  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import Shop from "./components/Shop.vue"
import Footer from "./components/Footer.vue"
import Social from "./components/Social.vue"


export default {
  name: 'App',
  components: {

    Header,
    Main,
    Shop,
    Footer,
    Social
  
  }
}
</script>

<style lang="scss">
  @import "./assets/style/generals.scss"
</style>
