<template>
  <footer>
    <section></section>
    <section class="text-center">
      
      <p>&copy; Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>
      
    </section>
  </footer>
</template>

<script>
export default {
name : 'Footer',
props: ['sectionList'],
components:{
  // UpperFooter
}
}
</script>

<style lang='scss' scoped>
@import '../style/variables.scss';
footer{
  background-color: ivory;
}

</style>