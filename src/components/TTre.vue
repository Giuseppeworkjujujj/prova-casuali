<template>

  <div class="row-10">
    <div class="col-5 rar ">
      <img class="prima" src="../assets/item1(2).svg" alt="">
    </div>
    <div class="col-7 ror">
      <h3>Un luogo a invito con tutto lo spazio necessario per parlare</h3>
      <p>i server discord sono organizzati in canali tematici in cui puoi collaborare, condividere o semplicemente parlare della tua giornata senza intasare una chat di gruppo</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TTreSito',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss' scoped>
  .row-10{
    width: 100%;
    height: 450px;
    display: flex;
    .rar{
      display: flex;
      justify-content: center;
      align-items: center;
      .prima{
        width: 600px;
      }
    }
    .ror{
      position: relative;
      display: flex;
      justify-content: center;
      
      h3{
        position: absolute;
        top: 180px;
        width: 80%;
      }
      p{
        position: absolute;
        top: 255px;
        width: 80%;
      }
    }
    @media screen and (max-width:1300px){
      .rar{
      position: absolute;
      display: flex;
      justify-content: center;
      right: 0px;
      // border: 2px solid black;
      height: 460px;
      .prima{
        position: absolute;
        top: 50px;
        width: 100%;
      }

      }
    
    .ror{
      top: 475px;
      width: 100%;
      display: flex;
      justify-content: center;
      margin-left: 10px;
      margin-right: 10px;
      h3{
        top: -20px;
        width: 100%;
        text-align: center;
      }
      p{
        top: 20px;
        width: 100%;
        text-align: center;
      }  
    }
    }
      @media screen and (max-width:420px){
        .rar{
      display: flex;
      justify-content: center;
      // border: 2px solid black;
      height: 285px;
      .prima{
        position: absolute;
        top: 20px;
        left: 0px;
        width: 100%;
      }

      }
    
    .ror{
      top: 300px;
      width: 100%;
      display: flex;
      justify-content: center;
      margin-left: 10px;
      margin-right: 10px;
      h3{
        top: -15px;
        width: 100%;
        text-align: center;
      }
      p{
        top: 40px;
        width: 100%;
        text-align: center;
      }  
    }
    }   

  }
</style>