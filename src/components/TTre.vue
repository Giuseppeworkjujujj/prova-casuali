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
    }}
    @media screen and (max-width:1380px){
      .rar{
        padding-left: 100px;
      }
    }
    @media screen and (max-width:1175px){
      .row-10{
                
      .rar{
        width: 99%;
        display: flex;
        justify-content: center;
        margin-left: 0px;
        .prima{
          margin-left: -100px
        }
      }
      .ror{
        // width: 100%;
        position: absolute;
        top: 850px;
        width: 99%;
        text-align: center;

        h3{
          width: 100%;
        }

        p{
          margin-top: -40px;
        }
      }
    }}
      @media screen and (max-width:750px){
        .row-10{
        .rar{
      align-items: baseline;
      height: 285px;
      .prima{
        width: 380px;
      }

      }
    
    .ror{
    height: 200px;
      h3{
        top: 10px;
      }
      p{
        top: 110px;
      }  
    }
    }   
    
  }
  @media screen and (max-width:540px){
        .row-10{
        .rar{
      .prima{
        // margin-left: -100px;
      }
      }
    }   
    
  }
</style>