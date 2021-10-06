<template>
  <header>
    <section class="container">
      <div class="row">
        
        <Topnavbar />
        
        <div class="col-12 text-center">
          <a href="#"><img src="../assets/img/avada-food-logo.png" alt="Main Avada Logo"></a>
        </div>

        <Navbar />

      </div>
    </section>
  </header>
</template>

<script>
import Topnavbar from './TopHeaderNavbar.vue'

export default {
  name: 'Header',
  components : {
    Topnavbar,
    // Navbar,
  }
  //   msg: String
  // }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

</style>
