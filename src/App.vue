<template>
  <div id="app">
    <Testa/>
    <TDue/>
  </div>
</template>

<script>
import Testa from './components/Testa.vue'
import TDue from './components/TDue.vue'

export default {
  name: 'App',
  components: {
    Testa,
    TDue
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
