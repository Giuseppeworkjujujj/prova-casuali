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
        top: 220px;
        width: 80%;
      }
    }}
    @media screen and (max-width:1380px){
      .row-3{
      .prima{
        padding-left: 100px;
      }
      .ror{
        padding-right: 20px;
      }
    }
  }
    @media screen and (max-width:1175px){
      .row-3{
      .raar{
        width: 100%;
        display: flex;
        justify-content: center;
        // padding-left: -150px;
        margin-top: 150px;
        .prima{
          width: 700px;
        }
      }
      .roor{
        width: 100%;
        position: absolute;
        top: 1960px;
        width: 100%;
        text-align: center;

        // p{
        //   margin-top: -40px;
        // }
      }
    }
    }
    @media screen and (max-width:750px){
      .row-3{
        position: relative;
        // border: 2px solid green;
      .raar{
        // margin-left: 0px;
        // width: 100%;
        // display: flex;
        // justify-content: center;
        // margin-left: 0px;
        margin-top: -40px;
        // border: 2px solid red;
        height: 280px;
        .prima{
          width: 450px;
          margin-left: -80px;
          // height: 800px;
          // position: relative;
          // top: 10px;
        }
      }
      .roor{
        // border: 2px solid blue;
        width: 100%;
        position: absolute;
        top: 100px;
        height: 200px;
        // width: 100%;
        text-align: center;
    }
    }
  }
</style>