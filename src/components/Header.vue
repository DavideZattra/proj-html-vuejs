<template>
  <header>
    <section class="container">
      <div class="row">
        
        <div class="col-12 d-flex justify-content-between align-items-center">
    
          <ul class="d-flex p-0 ">

            <li class="pt-2 ps-2 pe-2"><a href="#">Download App</a></li>
            <li class="pt-2 ps-2 pe-2"><a href="#">Advertise with us</a></li>

          </ul>

          <ul class="d-flex p-0">

            <li class="pt-2 ps-2 pe-2"><a href="#"><i class="fab fa-facebook"></i></a></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"><i class="fab fa-instagram"></i></a></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"><i class="fab fa-twitter"></i></a></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"><i class="fab fa-youtube"></i></a></li>

          </ul>

        </div>
        
        <div class="col-12 text-center">
          <a href="#"><img src="../assets/img/avada-food-logo.png" alt="Main Avada Logo"></a>
        </div>

        <div class="col-12 pb-2">

          <nav>

            <ul class="d-flex justify-content-center">

              <li v-for="(element, index) in sectionList" :key="index">
                <a class="text-capitalize pb-3" :class="{active : element.selected}" :href="element.url">
                  {{ element.name }}
                </a>                                
              </li>

            </ul>

          </nav>

        </div>

      </div>
    </section>
  </header>
</template>

<script>

export default {
  name: 'Header',

  props : ['sectionList'],

  components : {
  },

  
  
  //   msg: String
  // }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

.active{
  color: $mainOrangeColor;
  border-bottom: 2px solid $mainOrangeColor;
}
</style>
