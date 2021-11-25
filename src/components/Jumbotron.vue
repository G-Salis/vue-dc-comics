<template>
  <div class="jumbotron">
  
  <div class="box">
    <h3>CURRENT SERIES</h3>
  </div>>

    
  </div>
</template>

<script>
export default {

    name: "Main"
  
}
</script>

<style scoped>
   .jumbotron{
    height: 530px;
    background-image: url('../assets/img/jumbotron.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
  }
  .box{
    background-color: #0282F9;
    color: white;
    height: 50px;
    position: absolute;
    left: 167px;
    bottom: -25px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  h2{
    padding: 5px
  }
 

</style>
