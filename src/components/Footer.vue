<template>
  <footer>
    <!-- section with all info about avada social links and store link -->
    <section id="ms_upper-footer" class="container">
      <div class="row justify-content-center pt-5 pb-5">
        <div id="ms_social" class="col-3 border-end">
          <a href="#"><img class="" src="../assets/img/avada-food-logo-mob.png" alt="Main Avada Logo"></a>
          <ul class="d-flex p-0">

            <li class="pt-2 ps-2 pe-2"><a href="#"></a><i class="fab fa-facebook"></i></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"></a><i class="fab fa-instagram"></i></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"></a><i class="fab fa-twitter"></i></li>
            <li class="pt-2 ps-2 pe-2"><a href="#"></a><i class="fab fa-youtube"></i></li>

          </ul>
        </div>
        <div class="col-3 border-end">
          <ul>
            <li class="text-capitalize pb-2" v-for="(element, index) in sectionList" :key="index">
              <a :href="element.url"> {{ element.name }}</a>
            </li>
          </ul>
        </div>
        <div id="ms_contacts" class="col-3 border-end">
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
        <div id="ms_appStore" class="col-3 ">
          <h5>get our app!</h5>
          <img class="img-fluid" src="../assets/img/download-android.png" alt="">
          <img class="img-fluid" src="../assets/img/download-app-store.png" alt="">
          
        </div>
      </div>

    </section>

    <!-- Copyright Section and button to go on the top of page -->
    <section id="ms_lower-footer" class="text-center">

      <a href="#">&uarr;</a>
      
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
  background-color: white;


  #ms_upper-footer{
    h5{
      font-size: 0.9rem;
      text-transform: uppercase;
      color: $mainOrangeColor;
    }
    #ms_social{
      img{
        width: 90%;
      }
      i{
        padding-top: 25px;
        color: #6a6b6c;
      }
    }
  
    #ms_appStore{
      img{
        width: 90%;
        padding-bottom: 10px;
      }
    }
    #ms_contacts{

      color: #6a6b6c;
      i{
      padding-right: 10px;
    }
    }
  }

  #ms_lower-footer{
    position: relative;
    background-color: $mainLightGrayColor;
    height: 50px;

    a{
      position: absolute;
      top: 5px;
      left: 25px;
      display: inline-block;

      height: 35px;
      width: 35px;
      color: white;
      background-color: #6a6b6c;
      border-radius: 50%;
      line-height: 35px;

    }

    p{
      font-size: 0.5rem;
      line-height: 50px;
      margin: 0;
    }
  }
}


</style>