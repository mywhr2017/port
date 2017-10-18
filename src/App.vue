<template>
  <div id="app">
    <otext></otext>
    <ddd></ddd>
  </div>
</template>

<script>
import Otext from '@/components/otext'
import Ddd from '@/components/ddd'
export default {
  name: 'app',
   components:{Otext,Ddd}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
