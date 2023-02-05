<template>

  <div class="row-3">
    <div class="col-5 raar ">
      <img class="prima" src="../assets/item3(1).svg" alt="">
    </div>
    <div class="col-7 roor">
      <h3>Da pochi a un fandom</h3>
      <p>Dai inizio a una community di qualsiasi dimensione con strumenti di moderazione e accesso ai membri personalizzabile. Concedi ai membri poteri speciali, crea canali privati, e molto altro</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TCinqueSito',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss' scoped>
  .row-3{
    width: 100%;
    height: 450px;
    display: flex;
    .raar{
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 450px;
      .prima{
        width: 600px;
      }
    }
    .roor{
      position: relative;
      height: 450px;
      display: flex;
      justify-content: center;

      
      h3{
        position: absolute;
        top: 180px;
        width: 80%;
      }
      p{
        position: absolute;
        top: 250px;
        width: 80%;
      }
    }
    // @media screen and (max-width:1300px){
    //   .rar{
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
    
    // .ror{
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
    //   @media screen and (max-width:420px){
    //     .rar{
    //   display: flex;
    //   justify-content: center;
    //   // border: 2px solid black;
    //   height: 285px;
    //   .prima{
    //     position: absolute;
    //     top: 20px;
    //     left: 0px;
    //     width: 100%;
    //   }

    //   }
    
    // .ror{
    //   top: 300px;
    //   width: 100%;
    //   display: flex;
    //   justify-content: center;
    //   margin-left: 10px;
    //   margin-right: 10px;
    //   h3{
    //     top: -15px;
    //     width: 100%;
    //     text-align: center;
    //   }
    //   p{
    //     top: 40px;
    //     width: 100%;
    //     text-align: center;
    //   }  
    // }
    // }   

  }
</style>