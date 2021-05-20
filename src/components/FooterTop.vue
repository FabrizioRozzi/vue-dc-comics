<template>
  
  <div>
    <div class="container-80">
      <div class="container-50">
      <ul>
        <li>
          <h3>dc comics</h3>
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
          <h3>shop</h3>
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
          <h3>dc</h3>
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
          <h3>sites</h3>
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
      <div class="logo">
        
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name:'FooterTop.vue'
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
        h3{
          text-transform: uppercase;
          color: white;
        }
      }
      
    }
  }
  a{
    color: #7C7566;
  }
  .logo{
    width: 50%;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat:no-repeat;
    background-size: 600px 600px;
    background-position: 0 -110px ;
  }
</style>