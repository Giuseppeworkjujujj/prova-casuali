<template>

  <div class="row-9">
    <div class="col-4">
      <h3>Il tuo posto per parlare</h3>
      <p> &#127470;&#127481; Italiano</p>
      <ul class="icon">
        <li><i class="fa-brands fa-facebook"></i></li>
        <li><i class="fa-brands fa-twitter"></i></li>
        <li><i class="fa-brands fa-instagram"></i></li>
        <li><i class="fa-brands fa-youtube"></i></li>
      </ul>
      <hr class="border  border-2 opacity-75">
      <img src="../assets/logo(1).svg" alt="">
    </div>
    <div class="col-2">
      <h4>Prodotto</h4>
      <ul>
        <li>Scarica</li>
        <li>Perchè Discord</li>
        <li>Nitro</li>
        <li>sicurezza</li>
        <li>Assistenza</li>
      </ul>
    </div>
    <div class="col-2">
      <h4>Compagnia</h4>
      <ul>
        <li>Chi siamo</li>
        <li>Lavora con noi</li>
        <li>Marchio</li>
        <li>Redazione</li>
        <li>Negozio</li>
      </ul>
    </div>
    <div class="col-2">
      <h4>Risorse</h4>
      <ul>
        <li>Perchè Discord</li>
        <li>Lavora con noi</li>
        <li>Sicurezza</li>
        <li>Redazione</li>
        <li>Assistenza</li>
        <li>Negozio</li>
      </ul>
    </div>
    <div class="col-2">
      <h4>Norme</h4>
      <ul>
        <li>Chi siamo</li>
        <li>Lavora con noi</li>
        <li>Marchio</li>
        <li>Redazione</li>
        <li>Negozio</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TSetteSito',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss' scoped>
.row-9{
  background-color: black;
  display: flex;
  height: 320px;
  .col-4{
    h3{
      margin-top: 60px;
      margin-left: 20px;
      color: white;
    }
    p{
      font-size: 18px;
      margin-left: 20px;
      margin-top: 20px;
      color: white;
    }
       .icon{
      // border: 2px solid white;
      // width: 250px;
      padding-left: 0px;
    
      li{
        list-style: none;
        display: inline;
        color: white;
        font-size: 25px;
        margin-left: 20px;
      }
    }
    hr{
      width: 105%;
      color: gray;
    }
    img{
      height: 50px;
      margin-left: 20px;
    }
  }
  .col-2{
    h4{
      margin-left: 90px;
      margin-top: 20px;
      color: gray;
      // font-weight: bold;
      font-size: 20px;
    }
    li{
      list-style: none;
      color: white;
      margin-left: 60px;
      line-height: 15px;
      padding-top: 25px;
    }
  }
}
@media screen and (max-width:1175px){
  .row-9{
    display: flex;
    justify-content: center;
    text-align: center;
    .col-4{
      width: 80%;
    h3{
      width: 100%;
      font-size: 40px;
    }
    hr{
      display: none;
    }
    ul{
       width: 100%;
    .icon{
    }
    }
    img{
      // position: absolute;
      // margin-top:50px
    }
  }
  
  
  .col-2{
        display: none;
      }
    }
    }
  //   @media screen and (max-width:750px){
  // .row-9{
    
  //   .col-4{
  //     border: 2px solid red;
  //     width: 100%;
  //     display: flex;
  //     justify-content:center;
      
      
  //     h3{
  //       // border: 2px solid red;
  //       width: 130%;
  //       margin-left: -15px;
  //       font-size: 30px;
  //     }
  //     .icon{
  //       // border: 2px solid red;
  //       text-align: center;
  //       display: flex;
  //       justify-content: center;
  //       margin-left: 5px;
  //     }
  //       img{
  //         // border: 2px solid red;
  //         margin-left: 10px;
  //       }
            
  //   }

  // }    
  //   }
    @media screen and (max-width:510px){
  .row-9{
    // position: relative;
    .col-4{
      h3{
      margin-top: 20px;
      font-size: 40px;
      }
      
            
    }

  }    
    }
</style>