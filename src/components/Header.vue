<template>
  <div class="header-full">
    <nav>
      <ul><img class="img-dim" src="../assets/dc-logo.png"/>
          <!-- <li class="img-list"><img class="img-dim" src="../assets/dc-logo.png" width="50"/></li> -->
          <li>CHARACTERS</li>
          <li>COMICS</li>
          <li>MOVIES</li>
          <li>TV</li>
          <li>GAMES</li>
          <li>COLLECTIBLES</li>
          <li>VIDEOS</li>
          <li>FANS</li>
          <li>NEWS</li>
          <li>SHOP</li>
        </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>
<style lang="scss" scoped>
.header-full{
  nav{
    margin-top: 30px;
    ul{
        display:flex;
        list-style: none;
        margin-left:500px;
         li{
           .img-dim{
            //  margin-right:800px;
           }
          margin-left: 8px;
          font-size: 14px;
          height: 40px;

          &:hover{
            color: rgb(14, 100, 228);
            border-bottom:  3px solid rgb(14, 100, 228);
          }
         }
      }
  }
}

</style>
