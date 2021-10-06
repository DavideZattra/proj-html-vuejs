<template>
  <footer>
    <section id="ms_upper-footer" class="container-fluid">
      <div class="row justify-content-center pt-5 pb-5">
        <div class="col-2">
          <a href="#"><img src="../assets/img/avada-food-logo.png" alt="Main Avada Logo"></a>
          <ul class="d-flex p-0">

            <li class="pt-2 ps-2 pe-2"><a href="#"></a><i class="fab fa-facebook"></i></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"></a><i class="fab fa-instagram"></i></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"></a><i class="fab fa-twitter"></i></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"></a><i class="fab fa-youtube"></i></li>

          </ul>
        </div>
        <div class="col-2">
          <ul>
            <li class="text-capitalize pb-2" v-for="(element, index) in sectionList" :key="index">
              <a :href="element.url"> {{ element.name }}</a>
            </li>
          </ul>
        </div>
        <div class="col-2">
          <h5>contact</h5>
          <ul class="p-0">
            <li class="d-flex">
              <p><i class="fas fa-map-marker-alt"></i></p>
              <p>775 New York Ave, Brooklyn Kings, New York 11203</p>

            </li>
            <li class="d-flex">
              <p><i class="fas fa-phone"></i></p>
              <p>+ 0100-505-0000</p>
            </li>
            <li class="d-flex">
              <p><i class="fas fa-envelope"></i></p>
              <p>info@your-domain.com</p>
            </li>
          </ul>
        </div>
        <div class="col-2">
          <h5>get our app!</h5>
          <ul>
            <li>
              <a href="#"><img class="img-fluid" src="../assets/img/download-app-store.png" alt=""></a>
            </li>
            <li>
              <a href="#"><img class="img-fluid" src="../assets/img/download-android.png" alt=""></a>
            </li>
          </ul>
        </div>
      </div>

    </section>
    <section id="ms_lower-footer" class="text-center">
      
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

#ms_upper-footer{
  h5{
    text-transform: uppercase;
    color: $mainOrangeColor;
  }
}

</style>