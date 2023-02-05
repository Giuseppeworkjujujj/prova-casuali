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
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>
