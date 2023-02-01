<template>
 <div class="container-fluid">
  <div class="row ">
    <div class="col-4 d-flex justify-content-center align-items-center">
      <img src="../assets/logo(1).svg" alt="">
    </div>
    <div class="col-6 ">
      <ul class="d-flex justify-content-between align-items-center">
        <li>Scarica</li>
        <li>Perchè Discord</li>
        <li>Nitro</li>
        <li>Sicurezza</li>
        <li>Assistenza</li>
      </ul>
    </div>
    <div class="col-2 d-flex justify-content-center align-items-center">
      <button class="btn btn-light">Accedi</button>
    </div>
  </div>
 </div>
</template>

<script>
export default {
  name: 'TestaSito',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss' scoped>
  .container-fluid{
    height: 100px;
    background-color: #265ee9;
    width: 100%;
  
    img{
      height: 50px;
    }
    ul{
      list-style: none;
      height: 100px;
      li{
        color: white;
      }
    }
    .col-2{
      height: 100px;
      button{
        color: #265ee9;
      }
    }
  }
  @media screen and (max-width:991px){
    li{
      display: none;
    }
  }
  @media screen and (max-width:570px){
    img{
      margin-left: 70px;
    }
    button{
      margin-right: 50px;
      margin-top: 10px;
    }
  }
</style>
