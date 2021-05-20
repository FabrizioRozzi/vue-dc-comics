<template>
  <div class="all">
    <div class="container-80">
      <div class="left">
        <button><h3>SIGN-UP NOW!</h3></button>
      </div>
      <div class="right">
        <ul>
          <li>
            <h3>FOLLOW US</h3>
          </li>
          <li>
            <img src="../assets/img/footer-facebook.png" alt="Facebook">
          </li>
          <li>
            <img src="../assets/img/footer-twitter.png" alt="Facebook">
          </li>
          <li>
            <img src="../assets/img/footer-youtube.png" alt="Facebook">
          </li>
          <li>
            <img src="../assets/img/footer-pinterest.png" alt="Facebook">
          </li>
          <li>
            <img src="../assets/img/footer-periscope.png" alt="Facebook">
          </li>
        </ul>
      </div>
    </div>
  </div>
  
</template>

<script>
export default {
  name:'FooterBottom'
}
</script>

<style lang="scss" scoped>
  .all{
    background-color: #303030;
    height: 100px;
    .container-80{
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      .left{
        button{
          background-color: #303030;
          border: 2px solid #0282F9;
          h3{
            color: white;
          }
        }
      }
      .right{
        ul{
          li{
            display: inline-block;
            padding: 0 10px;
            h3{
              color: #0282F9;
            }
            img{
              margin-top: 5px;
            }
          }
        }
       
        
      }
    }
  }
  

</style>