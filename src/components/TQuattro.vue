<template>

  <div class="row-2">
    <div class="col-6 rir">
      <h3>Dove trovarsi è facile</h3>
      <p>Mettiti comodo in un canale vocale quando hai tempo. Gli amici nel tuo server possono vedere che sei li e unirsi istantaneamente senza dover chiamare</p>
    </div>
    <div class="col-6 rer ">
      <img class="prima-1" src="../assets/item2.svg" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'TQuattroSito',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss' scoped>
  .row-2{
    display: flex;
    height: 450px;
    width: 100%;
    .rer{    
      display: flex;
      justify-content: center;
      align-items: center;
      height: 450px;
      float: right;
      .prima-1{
        width: 600px;
      }
    }
    .rir{
      position: relative;
      height: 450px;
      display: flex;
      justify-content: flex-end;    
      
      h3{
        position: absolute;
        top: 180px;
        width: 75%;
      }
      p{
        position: absolute;
        top: 220px;
        width: 75%;
      }
    }}
    @media screen and (max-width:1380px){
      .rer{
        margin-right: 300px;
      }
    }
    @media screen and (max-width:1175px){
      .row-2{
      .rir{
        width: 100%;
        display: flex;
        justify-content: center;
        margin-top: -100px;
        // margin-left: -50px;
        text-align: center;
        // border: 2px solid red;
      }
      .rer{
        width: 100%;
        position: absolute;
        
        // position: relative;
        margin-top: 150px;
        // margin-left: -50px;

        // top: 200px;
        width: 100%;
        text-align: center;

        p{
          margin-top: -40px;
        }
      }
    }}
    // @media screen and (max-width:1300px){
    //   .rer{
    //   position: absolute;
    //   display: flex;
    //   justify-content: center;
    //   right: 0px;
    //   // border: 2px solid black;
    //   height: 460px;
    //   .prima{
    //     position: absolute;
    //     top: 50px;
    //     width: 100%;
    //   }

    //   }
    
    // .rir{
    //   top: 475px;
    //   width: 100%;
    //   display: flex;
    //   justify-content: center;
    //   margin-left: 10px;
    //   margin-right: 10px;
    //   h3{
    //     top: -20px;
    //     width: 100%;
    //     text-align: center;
    //   }
    //   p{
    //     top: 20px;
    //     width: 100%;
    //     text-align: center;
    //   }  
    // }
    // }
      @media screen and (max-width:750px){ 
    .row-2{
      .rer{
    //   position: absolute;
    //   display: flex;
    //   justify-content: center;
    //   right: 0px;
    //   // border: 2px solid black;
      height: 280px;
    top:900px;
    // border: 2px solid green;
      .prima-1{
    //     position: absolute;
    //     top: 50px;
        width: 370px;
      }

      }
    
    .rir{
      top: 200px;
      // border: 2px solid red;
      height: 200px;
    //   width: 100%;
    //   display: flex;
    //   justify-content: center;
    // align-items: baseline;
    //   margin-left: 10px;
    //   margin-right: 10px;
      h3{
    //     top: -20px;
    //     width: 100%;
    //     text-align: center;
      }
      p{
    //     top: 20px;
    //     width: 100%;
    //     text-align: center;
      }  
    }
      }
    }
  
    
       

  
</style>