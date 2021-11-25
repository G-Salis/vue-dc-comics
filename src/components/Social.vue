<template>
  <section>

    <div class="container">
        <button>SIGN-UP NOW!</button>
        <div>
          <span>FOLLOW US</span>
          <img
          v-for="(card, index) in productSocial" 
          :key="`ciclo-social${index}`"
          :src="card.img" alt=""
          >
          
        </div>
      </div>
  </section>
</template>

<script>

import productSocial from '../assets/data/productSocial.js';

export default {

    name: "Social",


    data(){
    return{
      productSocial
    }
  
  }
  
}
</script>

<style scoped>
  section{
    background-color: #303030;
    min-height: 100px;
  }

  button{
    background-color: #303030;
    border: 2px solid #0282F9;
    color: white;
    padding: 10px;
    cursor: pointer;
   }

   img{
     margin: 0px 10px;
   }

   span{
     font-size: 25px;
     color: #0282F9;
     font-weight: 900;
     vertical-align: super;
   }

</style>
