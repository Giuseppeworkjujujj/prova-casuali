<template>

  <div class="row-8">
    <div class="col-12 roooor">
    <h3>PRONTO A INIZIARE LA TUA AVVENTURA</h3>
    </div>
    <div class="col-12 rerr">
      <button class="btn btn-primary mx-1 d-flex align-items-center" disabled>Scarica per Mac</button>
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
  .row-8{
    height: 200px;
    background-image: url("../assets/stars(3).svg");
    background-size:70%;
    background-repeat:no-repeat;
    background-position: top  ;
    .roooor{
      h3{
        text-align: center;
        padding-top: 30px;
      }
    }
    .rerr{
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }
  }
  @media screen and (max-width:1175px){
      .roooor{
        // width: 100%;
        // display: flex;
        // justify-content: center;
        // margin-left: -50px;
        margin-top: -150px;
      }

    }
    @media screen and (max-width:750px){
      .row-8{
        background-size: 90%;
      .roooor{
        width: 100%;
        // display: flex;
        // justify-content: center;
        // margin-left: -50px;
        margin-top: -250px;
        h3{
          font-size: 20px;

        }
      }
    }
    }
</style>