<template>

  <div class="row">
      <div class="col-12 d-flex justify-content-center">
        <div class="col-12-2 d-flex justify-content-center">
          <h1 class="">Il tuo posto per parlare</h1>
        </div>
        <div class="col-12-3 d-flex justify-content-center">
          <p>Che tu faccia parte di un club scolastico, gruppo gamer, comunità artistica mondiale o semplicemente di un piccolo gruppo di amici che vuole passare il tempo assieme, Discord rende più facile chiaccherare ogni giorno e ritrovarsi più spesso.</p>
        </div>
        <div class="col-12-4 d-flex justify-content-center">
          <button class="btn btn-light mx-1 d-flex align-items-center">Scarica per Mac</button>
          <button class="btn btn-dark mx-1 d-flex align-items-center">Apri discord nel tuo browser</button>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'TDueSito',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss' scoped>
 .row{
    height: 510px;
    width: 100%;
    
    margin-left: 0px;
    background-image: url("../assets/jumbo.png");
    background-size: cover;
    background-repeat:no-repeat;
    background-position: left  top  ;
    background-color: #265ee9;
       .col-12-2{
        
        position: absolute;
        width: 50%;
        top: 205px;
        h1{
          font-size: 60px;
          color: white;
        }
       } 
       .col-12-3{
        position: absolute;
        width: 45%;
        top: 290px;
        text-align: center;
        p{
          font-size: medium;
          color: white;
        }
       }
       .col-12-4{
        height: 38px;
        position: absolute;
        width: 100%;
        top: 390px;
       }
       @media screen and (max-width:1220px){
        .col-12-3{
        position: absolute;
        width: 60%;
        top: 290px;
        text-align: center;
        p{
          font-size: medium;
          color: white;
        }
       }
       .col-12-4{
        position: absolute;
        top: 450px;
       }
        h1{
        position: absolute;
        top:-50px;
        text-align: center;
       }
       p{
        position: absolute;
        top: 30px;
        width: 80%;
       }

      }
      @media screen and (max-width:800px){
        .row{
        background-size: 1500px 100%;
       }
       .col-12-2{
        
        position: absolute;
        width: 100%;
        top: 205px;
        h1{
          font-size: 50px;
          color: white;
        }
       } 
       .col-12-3{
        position: absolute;
        width: 100%;
        top: 270px;
        text-align: center;
        p{
          font-size: medium;
          color: white;
        }
       }
       .col-12-4{
        visibility: hidden;
      }
  }
}
   
   
</style>