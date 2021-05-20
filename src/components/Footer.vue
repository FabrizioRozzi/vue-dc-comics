<template>
  
  <div>
    <div class="container-80">
      <div class="container-50">
      <ul>
        <li>
          <h1>dc comics</h1>
        </li>
        <li>
          <a href="#">Characters</a>
        </li>
        <li>
          <a href="#">Comics</a>
        </li>
        <li>
          <a href="#">Movies</a>
        </li>
        <li>
          <a href="#">TV</a>
        </li>
        <li>
          <a href="#">Games</a>
        </li>
        <li>
          <a href="#">Videos</a>
        </li>
        <li>
          <a href="#">News</a>
        </li>
        <li>
          <h1>shop</h1>
        </li>
        <li>
          <a href="#">Shop DC</a>
        </li>
        <li>
          <a href="#">Shop DC Collectibles</a>
        </li>
      </ul>
      <ul>
        <li>
          <h1>dc</h1>
        </li>
        <li>
          <a href="#">Terms Of Use</a>
        </li>
        <li>
          <a href="#">Privacy Policy (New)</a>
        </li>
        <li>
          <a href="#">Add Choices</a>
        </li>
        <li>
          <a href="#">Advertising</a>
        </li>
        <li>
          <a href="#">Jobs</a>
        </li>
        <li>
          <a href="#">Subscriptions</a>
        </li>
        <li>
          <a href="#">Talent Workshops</a>
        </li>
        <li>
          <a href="#">CPSC Certificates</a>
        </li>
        <li>
          <a href="#">Ratings</a>
        </li>
        <li>
          <a href="#">Shop Help</a>
        </li>
        <li>
          <a href="#">Contact Us</a>
        </li>
      </ul>
      <ul>
        <li>
          <h1>sites</h1>
        </li>
        <li>
          <a href="#">DC</a>
        </li>
        <li>
          <a href="#">MAD Magazine</a>
        </li>
        <li>
          <a href="#">DC Kids</a>
        </li>
        <li>
          <a href="#">DC Universe</a>
        </li>
        <li>
          <a href="#">DC Power Visa</a>
        </li>
      </ul>
      </div>
      <div>
        <img src="../assets/img/dc-logo-bg.png" alt="Logo footer">
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name:'Footer.vue'
}
</script>

<style lang="scss" scoped>
  div{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: contain;
    div{
      display: flex;
      justify-content: flex-start;
      align-items: center;
      height: 400px;
      .container-50{
        display: flex;
        align-items: flex-start;
        h1{
          text-transform: uppercase;
          color: white;
        }
      }
      
    }
  }
  a{
    color: #7C7566;
  }
  img{
    
    height: 600px;
  }
</style>