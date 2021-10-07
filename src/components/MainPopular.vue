<template>
  <section id="ms_popular-recipes" class="container">
      <div class="row justify-content-center">

          <div class="col-12 text-center">
              <h5>Popular recipes</h5>
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iusto magni soluta maiores.</p>
          </div>
          <div class="col-6 ps-0">
              <div class="ms_main-card">
                <img class="img-fluid" src="../assets/img/Yogurt-Nan.jpg" alt="Yogurt Nan">
                <div class="ms_main-card-txt ">
                    <h5>Lunch Facourite with Salad, Naan And Beans</h5>
                    <pre>Bakery, Featured, Healty, Latest Recipes, Staff Picks</pre>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas possimus velit tempora rerum maiores. Enim dicta corporis placeat? Eveniet in ullam sapiente explicabo minus, ratione excepturi ut eos impedit quas vitae itaque maxime tempore quisquam animi pariatur, esse harum quia quaerat maiores ea sed dolorum. Illum nobis esse laborum animi.</p>
                    <button class="btn">Learn More</button>
                </div>
              </div>
          </div>
          <div class="col-6 pe-0 d-flex flex-wrap justify-content-between ">

              <div class="ms_img-container pe-2">
                  <img class="" src="../assets/img/Mixed-fruits.jpg" alt="">
              </div>
              <div class="ms_img-container ps-2">
                  <img class="" src="../assets/img/r-rachel-park-366508-unsplash-min.jpg" alt="">
              </div>
              <div class="ms_img-container pe-2">
                  <img class="" src="../assets/img/r-michelle-tsang-500721-unsplash-min.jpg" alt="">
              </div>
              <div class="ms_img-container ps-2">
                  <img class="" src="../assets/img/quick-summer-drink-460x295.jpg" alt="">
              </div>
              <div class="ms_img-container pe-2">
                  <img class="" src="../assets/img/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="">
              </div>
              <div class="ms_img-container ps-2">
                  <img class="" src="../assets/img/perfect-cosmopolitan-460x295.jpg" alt="">
              </div>
              <div class="ms_img-container pe-2">
                  <img class="" src="../assets/img/fi2x-6-460x295.jpg" alt="">
              </div>
              <div class="ms_img-container ps-2">
                  <img class="" src="../assets/img/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="">
              </div>
              
          </div>

      </div>
  </section>
</template>

<script>
export default {
name : 'PopularRecipes'
}
</script>

<style lang='scss' scoped>
@import '../style/variables.scss';

.ms_main-card{
    height: 100%;
    background-color: white;

    .ms_main-card-txt{
        padding: 1rem;


        button{
            color: white;
            background-color: $mainOrangeColor;
            border-radius: 0;
        }
    }
}

.ms_img-container{
    
    flex-basis: 50%;
    margin-bottom: 16px;

    img{
        width: 100%;
    }
}
</style>