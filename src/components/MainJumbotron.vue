<template>
  <section id="ms_jumbotron">
      <TodayPicks />
  </section>
</template>

<script>
import TodayPicks from './JumbotronPicks.vue'

export default {
name : 'Jumbotron',
components : {
    TodayPicks,
    // FoodieJournal
}
}
</script>

<style lang='scss' scoped>
#ms_jumbotron{
    position: relative;
    height: 475px;
    background-image: url('../assets/img/single-post-img3.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
</style>