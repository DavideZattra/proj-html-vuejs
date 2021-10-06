<template>
  <header>
    <section class="container">
      <div class="row">
        
        <Topnavbar />
        
        <div class="col-12 text-center">
          <a href="#"><img src="../assets/img/avada-food-logo.png" alt="Main Avada Logo"></a>
        </div>

        <div class="col-12 pb-2">

          <nav>

            <ul class="d-flex justify-content-center">

              <li v-for="(element, index) in sectionList" :key="index">
                <MainNavbarItem  :element='element'/>
                               
              </li>

            </ul>

          </nav>

        </div>

      </div>
    </section>
  </header>
</template>

<script>
import Topnavbar from './HeaderTopNavbar.vue';
import MainNavbarItem from './HeaderMainNavbar.vue';

export default {
  name: 'Header',

  props : ['sectionList'],

  components : {
    Topnavbar,
    MainNavbarItem,
  },

  
  
  //   msg: String
  // }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

</style>
