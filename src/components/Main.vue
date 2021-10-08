<template>
  <main>
    <Jumbotron :foodieJournal="foodieJournal"/>
    <Popular />
    <Collection />
    <FarmToTable />
    <Subscribe />
  </main>
</template>

<script>
import Jumbotron from './MainJumbotron.vue';
import Popular from './MainPopular.vue';
import Collection from './MainCollection.vue';
import FarmToTable from './MainFarmToTable.vue';
import Subscribe from './MainSubscribe.vue';

export default {
name : 'Main',
props : ['foodieJournal'],
components :{
  Jumbotron,
  Popular,
  Collection,
  FarmToTable,
  Subscribe
  }
}
</script>

<style lang='scss' scoped> 
@import '../style/variables.scss';

main{
  min-height: 100vh;
  background-color: $mainLightGrayColor;
}
</style>