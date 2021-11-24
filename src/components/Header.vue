<template>
  <header>

   <div class="container">
    <div>
      <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div>
      <ul>
        <li
        v-for="(link, index) in links" 
        :key="`ciclo-nav${index}`"
        ><a href="#">{{link.text}}</a></li>
      </ul>
    </div>
   </div>
    
  </header>
</template>

<script>
export default {

    name: "Header",

    data(){
    return{
      links:[
        {
          url: "/characters",
          text: "characters",
          current: false,
        },
        {
          url: "/comic",
          text: "comic",
          current: false,
        },
        {
          url: "/movies",
          text: "movies",
          current: false,
        },
        {
          url: "/tv",
          text: "tv",
          current: false,
        },
        {
          url: "/games",
          text: "games",
          current: false,
        },
        {
          url: "/collectibles",
          text: "collectibles",
          current: false,
        },
        {
          url: "/videos",
          text: "videos",
          current: false,
        },
        {
          url: "/fans",
          text: "fans",
          current: false,
        },
        {
          url: "/news",
          text: "news",
          current: false,
        },
        {
          url: "/shop",
          text: "shop",
          current: false,
        },
      ]
    }
  
  }
}
</script>

<style lang="scss">


  header{
    background-color: white;
    height: 150px;
  }

</style>
