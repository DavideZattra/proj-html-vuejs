<template>
  <header>
    <section class="container">
      <div class="row">
        
        <Topnavbar />
        
        <div class="col-12 text-center">
          <a href="#"><img src="../assets/img/avada-food-logo.png" alt="Main Avada Logo"></a>
        </div>

        <div class="col-12">

          <nav>

            <ul class="d-flex justify-content-center">

              <li v-for="(element, index) in sectionList" :key="index">
                <a class="text-capitalize" :class="{active : element.active}" :href="element.url">
                  {{ element.name }}
                </a>                
              </li>

            </ul>

          </nav>

        </div>
        <MainNavbar />

      </div>
    </section>
  </header>
</template>

<script>
import Topnavbar from './TopHeaderNavbar.vue';
import MainNavbar from './MainHeaderNavbar.vue';

export default {
  name: 'Header',

  components : {
    Topnavbar,
    MainNavbar,
  },

  data: function(){
    return{
      sectionList: [
        {
          name : 'home',
          url : '#',
          active : true,
        },
        {
          name : 'recipes',
          url : '#',
          active : false,
        },
        {
          name : 'places',
          url : '#',
          active : false,
        },
        {
          name : 'blog',
          url : '#',
          active : false,
        },
        {
          name : 'about',
          url : '#',
          active : false,
        },
        {
          name : 'contact',
          url : '#',
          active : false,
        },
      ]
    }
  }
  //   msg: String
  // }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';
.active{
  color: red;
  border-bottom: 2px solid red;
}
</style>
