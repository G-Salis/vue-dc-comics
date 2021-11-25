<template>
  <footer>
    <div class="bg-img">
      <div class="container">
          <div class="left-list">
            <div>DC COMICS</div>
            <ul>
              <li><a href="">Characters</a></li>
              <li><a href="">Games</a></li>
              <li><a href="">Comics</a></li>
              <li><a href="">Movies</a></li>
              <li><a href="">Films</a></li>
              <li><a href="">News</a></li>
              <li><a href="">TV</a></li>
            </ul>

          <div>SHOP</div>
            <ul>
              <li><a href="">Shop DC</a></li>
              <li><a href="">Shop DC Collectibles</a></li>
            </ul>
          </div>
        <div class="center-list">
          <div>DC</div>
          <ul>
            <li><a href="">Characters</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">Films</a></li>
            <li><a href="">News</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">Films</a></li>
            <li><a href="">News</a></li>
            <li><a href="">TV</a></li>
          </ul>
        </div>
        <div class="right-list">
          <div>SITES</div>
          <ul>
            <li><a href="">DC</a></li>
            <li><a href="">MAD Magazine</a></li>
            <li><a href="">DC Kids</a></li>
            <li><a href="">DC Universe</a></li>
            <li><a href="">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {

    name: "Footer"
  
}
</script>

<style scoped>

  footer{
    background-image: url('../assets/img/footer-bg.jpg');
    height: 400px;
  }

  .bg-img{
    background-image: url('../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: right;
    height: 400px;
    padding: 50px 0px;
  }

  .container{
    display: flex;
    justify-content: start;
    align-items: baseline;
    width: 80%;
    margin: 0 auto;
    min-height: 150px;
  }

  .left-list, .center-list, .right-list{
    margin-right: 15px
  }

  div {
  color: White;
  font-weight: 900;
  margin-bottom: 10px;
  }

  ul{
  display: block;
  list-style: none;
  color: darkgray;
  }

  li{
    margin-bottom: 15px;
    margin-left: 0px;
    line-height: 0px;
    border-bottom: 4px solid transparent;
  }
    li:hover{
      border-bottom:  4px solid transparent;
    
  }

    a{
      text-decoration: none;
      color: darkgray;
      font-size: 12px;
    }
    a:hover{
      color: #0282F9;
      cursor: pointer;

      }



</style>
