<template>
  <header>

   <div class="container">
    <div>
      <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div>
      <ul>
        <li
        v-for="(link, index) in productCard" 
        :key="`ciclo-nav${index}`"
        ><a href="#">{{link.text}}</a></li>
      </ul>
    </div>
   </div>
    
  </header>
</template>

<script>

import productCard from '../assets/data/productCard.js';

export default {

    name: "Header",

    data(){
    return{
      productCard
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
