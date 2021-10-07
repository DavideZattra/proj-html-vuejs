<template>
  <div id="ms_today-picks" class="text-center">
      <div class="ms_sticker">
          <h5 class="text-white text-uppercase m-0">Today's Pick</h5>
      </div>
      <h1>Food Corner: Top Japanese Restaurants for Sushi</h1>
      <h5>March 25, 2019</h5>
  </div>
</template>

<script>
export default {
name: 'TodayPicks'
}
</script>

<style lang='scss' scoped>
@import '../style/variables.scss';

#ms_today-picks{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);

    padding: 25px 25px;
    background-color: white;
    border-radius: 15px;
    .ms_sticker{
        position: absolute;
        top: -10%;
        left: 50%;
        transform: translateX(-50%);

        border-radius: 10px;
        padding: 0 25px;
        background-color: $mainOrangeColor;

        h5{
            font-weight: 700;
            font-size: 0.8em;
            line-height: 40px;
        }
    }
    
}
</style>