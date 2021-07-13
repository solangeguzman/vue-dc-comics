<template>
  <div class="container">
    <div class="text-margin">
       --Content goes here--
    </div>
    <div class="header-main">
      <ul>
         <li><img src="../assets/buy-comics-digital-comics.png" width="40" height="50">DIGITAL COMICS</li>
        <li><img src="../assets/buy-comics-merchandise.png" width="40" height="50" alt="">DC MERCHANDISE</li>
        <li><img src="../assets/buy-comics-subscriptions.png" width="40" height="50" alt="">SUBSCRIPTION</li>
        <li><img src="../assets/buy-comics-shop-locator.png" width="40" height="50" alt="">COMIC SHOP LOCATOR</li>
        <li><img src="../assets/buy-dc-power-visa.svg"  width="40" height="50" alt="">DC POWER VISA</li>
      </ul>
    </div>
    <div class="bg-main">
      <div class="list-box">
        <ul>
          <li>DC COMICS</li>
          <br>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
        <ul>
          <li>DC</li>
          <br>
          <li>Terms Of Use</li>
          <li>Privacy policy(News)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Rating</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
        <ul>
           <li>SITES</li>
           <br>
           <li>DC</li>
           <li>MAD Magazine</li>
           <li>DC Kids</li>
           <li>DC Universe</li>
           <li>DC Power Visa</li>
        </ul>
        <img class="img-logo-bg" src="../assets/dc-logo-bg.png" width="423">
      </div>
      <!-- img container -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main'
}
</script>

<style lang="scss" scoped>
.container{
  background: black;
  color: white;
  height: 70px;
   .text-margin{
    padding: 25px;
   }
   .header-main{
     background: rgba(0, 4, 255, 0.692);
     height: 100px;
     ul{
       display: flex;
       list-style: none;
       justify-content: center;
       li{
         margin-left:8px;
         padding: 20px;
         font-size: 10px;
       }
     }
   }
  .bg-main{
    background: url("../assets/footer-bg.jpg");
    height: 500px;
    .list-box{
      flex-flow: 1;
      display: flex;
      li{
        margin-left: 50px;
        list-style: none;
        widows: 300px;

      }
    }
    .img-logo-bg{
      margin-left: 400px;
    }
  }
}
</style>
