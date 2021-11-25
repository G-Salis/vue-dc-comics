<template>
  <div class="product-card">
    <img :src="product.thumb" :alt="product.type">
    <h3>{{product.series}}</h3>
  </div>
</template>

<script>
export default {
  name: 'ProductCard',
  props:{
    product: Object,
  }
}
</script>



<style lang="scss">
.product-card{
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  width: calc(100% / 6);
  margin-bottom: 20px;
  padding: 15px;
    
  img{
    height: 190px;
    margin-bottom: 10px;
    object-fit: cover;
    object-position: top;
    }
  }

</style>