<template>

  <div class="row-9">
    <div class="col-4">
      <h3>Il tuo posto per parlare</h3>
      <p>Italiano</p>
      <hr class="border border-primary border-3 opacity-75">
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
  }
  .col-2{
    h4{
      margin-left: 90px;
      margin-top: 20px;
      color: darkslateblue;
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
</style>