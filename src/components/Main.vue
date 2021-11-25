<template>
  <main>
    
    <div class="container">
      <Comics
          v-for="(product, index) in productsItems"  
          :key="index" 
          :product="product"
         />
    </div>
    <div class="container button-main">
      <button><a href="#">LOAD MORE</a></button>
    </div>
    
  </main>
</template>

<script>
import Comics from './Comics';
import productsItems from '../assets/data/productData.js';

export default {

    name: "Main",
     components:{
      Comics
    },

    data(){
    return{
      productsItems,
      
    }
  }
  
}
</script>

<style  lang="scss" scoped>
   main{
    background-color: black;
    color: white;
    min-height: 200px;
    padding: 20px 0px;
    
  }

  .container{
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    flex-wrap: wrap;
    width: 80%;
    margin: 0 auto;
    min-height: 150px;
  }

  .button-main{
      text-align: center;
      button{
        background-color: #0282F9;
        padding: 10px 60px;
        border: none;
        margin-top: 30px;
        cursor: pointer;
        margin: auto;
        a{
          color: white;
          text-decoration: none;
          font-weight: 700;
        }
      }
    }
 

</style>
