<template>
  <main>
    <Jumbotron />
  </main>
</template>

<script>
import Jumbotron from './MainJumbotron.vue'

export default {
name : 'Main',
components :{
  Jumbotron,
  // Popular,
  // Collection,
  // FarmToTable,
  // Hero
  }
}
</script>

<style lang='scss' scoped> 
main{
  height: 100vh;
  background-color: gray;
}
</style>