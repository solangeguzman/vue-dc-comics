<template>
  <div class="bg-footer">
    <div>
      <button class="button-sing">
       SING-UP NOW!
      </button>
    </div>
    <div class="section-final">
       <ul>
         <li class="text"><strong>FOLLOW US</strong></li>
         <li><img src="../assets/footer-facebook.png" alt=""></li>
         <li><img src="../assets/footer-twitter.png" alt=""></li>
         <li><img src="../assets/footer-youtube.png" alt=""></li>
         <li><img src="../assets/footer-pinterest.png" alt=""></li>
         <li><img src="../assets/footer-periscope.png" alt=""></li>
       </ul>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Footer'
}

</script>

<style lang="scss" scoped>
.bg-footer{
  background-color: rgb(43, 42, 42);
  height: 80px;
  display:flex;
  margin-top:520px;
  padding: 23px;
  .button-sing{
    background: rgb(43, 42, 42);
    border: blue solid 2px;
    height: 40px;
    color:white;
    padding: 8px;
    margin-left:200px;
  }
  .section-final{
    margin-left: 400px;
    .text{
    color:blue;
    margin-top: 12px;
  }
  ul{
    display: flex;
    list-style: none;
     li{
       margin: 5px;
     }
  }
  }
}
</style>
