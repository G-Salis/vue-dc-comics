<template>
  <div id="app">

    <Header/>
    <Jumbotron/>
    <Main/>
    <Shop/>
    <Footer/>
    <Social/>

  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Jumbotron from "./components/Jumbotron.vue"
import Main from "./components/Main.vue"
import Shop from "./components/Shop.vue"
import Footer from "./components/Footer.vue"
import Social from "./components/Social.vue"


export default {
  name: 'App',
  components: {

    Header,
    Jumbotron,
    Main,
    Shop,
    Footer,
    Social
  
  }
}
</script>

<style lang="scss">
  @import "./assets/style/generals.scss";
  @import "./assets/style/utilities.scss";
</style>
