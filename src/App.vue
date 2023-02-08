<template>
  <div id="app">
    <Testa/>
    <TDue/>
    <TTre/>
    <TQuattro/>
    <TCinque/>
    <TSei/>
    <TSette/>
    <TOtto/>
  </div>
</template>

<script>
import Testa from './components/Testa.vue'
import TDue from './components/TDue.vue'
import TTre from './components/TTre.vue'
import TQuattro from './components/TQuattro.vue'
import TCinque from './components/TCinque.vue'
import TSei from './components/TSei.vue'
import TSette from './components/TSette.vue'
import TOtto from './components/TOtto.vue'
import '@fortawesome/fontawesome-free/css/all.css'
import '@fortawesome/fontawesome-free/js/all.js'
export default {
  name: 'App',
  components: {
    Testa,
    TDue,
    TTre,
    TQuattro,
    TCinque,
    TSei,
    TSette,
    TOtto,
  },
 
}
</script>

<style>
*{
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
}
</style>
