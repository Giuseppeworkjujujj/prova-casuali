<template>
 <div class="container-fluid ">
  <div class="row">
      <div class="col-12 d-flex justify-content-center ">
        <img class="riga " src="../assets/jumbo.png" alt="">
        <div class="row-2 d-flex justify-content-center">
        <h1 class="">Il tuo posto per parlare</h1>
        </div>
        <div class="row-3 d-flex justify-content-center">
        <p>Che tu faccia parte di un club scolastico, gruppo gamer, comunità artistica mondiale o semplicemente di un piccolo gruppo di amici che vuole passare il tempo assieme, Discord rende più facile chiaccherare ogni giorno e ritrovarsi più spesso.</p>
        </div>
        <div class="row-4 d-flex justify-content-center">
        <button class="btn btn-light mx-2 ">Scarica per Mac</button>
        <button class="btn btn-dark mx-2">Apri discord nel tuo browser</button>
      </div>
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
 .container-fluid{
    height: 450px;
        img{
          height: 450px;
          // margin-left: -50px;
          // margin-right: -50px;
          // position: relative;
          




        }
       .row-2{
        
        position: absolute;
        width: 50%;
        top: 200px;
        h1{
          font-size: 60px;
          color: white;
        }
       } 
       .row-3{
        position: absolute;
        width: 50%;
        top: 280px;
        text-align: center;
        p{
          font-size: medium;
          color: white;
        }
       }
       .row-4{
        position: absolute;
        width: 50%;
        top: 380px;
       }
       @media screen and (max-width: 1920px),( min-width:1240px){
       .col-12{
        width: 100%;
        border: 2px solid red;
       }
        img{
          width:100%;
          height: 550px;
        }
       }
       @media screen and (max-width:1220px){
      
        h1{
        position: absolute;
        top:-80px;
        text-align: center;
        
       }
       .button{
        position: absolute;
        top:700px;
       }
      }
      @media screen and (max-width:830px){
       h1{
       
       }
      }
      }
   
   
</style>
