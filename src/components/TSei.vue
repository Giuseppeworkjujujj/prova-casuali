<template>

  <div class="row-7">
    <div class="col-12 rooor">
      <h3>Tecnologia affidabile per tenersi in contatto</h3>
      <p class="prim mx-auto">Video e audio a bassa latenza ti faranno sentire come se foste tutti nella stessa stanza. Fai ciao in video, guarda gli amici in streaming o riunitevi in una sessione di disegno con la condivisione del tempo </p>
       <!-- <p class="sec">una sessione di disegno con la condivisione del tempo.</p> -->
    </div>
    <div class="col-12 raaar ">
      <img class="prima-5" src="../assets/item4-big.svg" alt="">
    </div>
  </div>

</template>

<script>
export default {
  name: 'TSeiSito',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss' scoped>
  .row-7{
    height: 650px;
    .rooor{
      width: 100%;
   
      h3{
        text-align: center;
      }
      p{width: 80%;}
      .prim{
        text-align: center;
      }
    
    }
    .raaar{
      display: flex;
      justify-content: center;
    }
  }
  @media screen and (max-width:1175px){
    .row-7{  
    .raaar{
        width: 100%;
        display: flex;
        justify-content: center;
        margin-top: 400px;

        .prima-5{
          width: 800px;
        }
      }
      .rooor{
        position: absolute;
        margin-top: -100px;
      }
    }
    }
    @media screen and (max-width:750px){
    .row-7{  
      display: flex;
      justify-content: center;
    .raaar{
        width: 100%;
        margin-top: 150px;
        position: relative;
        .prima-5{
          width: 250px;
          position: absolute;
          top: 100px;
        }
      }
      .rooor{
        margin-top: 20px;
        width: 80%;
      }
    }
    }
</style>