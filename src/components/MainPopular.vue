<template>
  <section id="ms_popular-recipes" class="container">
      <div class="row justify-content-center">

          <div class="col-12 text-center">
              <h5 class="text-uppercase">Popular recipes</h5>
              <p class="pt-2 pb-3">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iusto magni soluta maiores.</p>
          </div>
          <div class="col-12 col-sm-6 ps-0">
              <div class="ms_main-card">
                <div class="ms_main-img">
                    <img class="img-fluid" src="../assets/img/Yogurt-Nan.jpg" alt="Yogurt Nan">
                    <div class="text-hover">
                        <a href="#"><i class="fas fa-link"></i></a>
                        <h5>Lunch Facourite with Salad, Naan And Beans</h5>
                    </div>
                </div>
                <div class="ms_main-card-txt ">
                    <h5>Lunch Facourite with Salad, Naan And Beans</h5>
                    <pre>Bakery, Featured, Healty, Latest Recipes, Staff Picks</pre>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas possimus velit tempora rerum maiores. Enim dicta corporis placeat? Eveniet in ullam sapiente explicabo minus, ratione excepturi ut eos impedit quas vitae itaque maxime tempore quisquam animi pariatur, esse harum quia quaerat maiores ea sed dolorum. Illum nobis esse laborum animi.</p>
                    <button class="btn">Learn More</button>
                </div>
              </div>
          </div>
          <div class="col-12 col-sm-6 pe-0 d-flex flex-wrap justify-content-between ">

              <div class="ms_img-container pe-2">
                  <img class="" src="../assets/img/Mixed-fruits.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>Fruit Platter with Banana, Mango, Berried and Orange</h5>
                  </div>
              </div>

              <div class="ms_img-container ps-2">
                  <img class="" src="../assets/img/r-rachel-park-366508-unsplash-min.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>There's a lot of food here!</h5>
                  </div>
              </div>

              <div class="ms_img-container pe-2">
                  <img class="" src="../assets/img/r-michelle-tsang-500721-unsplash-min.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>Green Tea IceCream: is Really Healty?</h5>
                  </div>
              </div>

              <div class="ms_img-container ps-2">
                  <img class="" src="../assets/img/quick-summer-drink-460x295.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>5 Quick summer Drinks Against the Heatawave</h5>
                  </div>
              </div>

              <div class="ms_img-container pe-2">
                  <img class="" src="../assets/img/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>Mixed Salads: When, Who, How and Why</h5>
                  </div>
              </div>

              <div class="ms_img-container ps-2">
                  <img class="" src="../assets/img/perfect-cosmopolitan-460x295.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>5 Tips for a Perfect Cosmopolitan</h5>
                  </div>
              </div>

              <div class="ms_img-container pe-2">
                  <img class="" src="../assets/img/fi2x-6-460x295.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>There's a lot of food here also!</h5>
                  </div>
              </div>

              <div class="ms_img-container ps-2">
                  <img class="" src="../assets/img/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>Nanny Pie: THE DEFINITIVE RECIPE</h5>
                  </div>
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

    .ms_main-img{
        position: relative;
        text-align: center; 
        overflow: hidden;      

        img{
          transition: transform .5s ease;
        }

        .text-hover{
        position: absolute;
        top: 0%;
        left: 0%;
        height: 100%;
        width: 100%;
        display: none;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 25px;
        color: white;
        background-image: linear-gradient(to top, $mainOrangeColor, #fc742594);

            a{
                display: inline-block;
                width: 35px;
                line-height: 35px;

                border-radius: 50%;
                background-color: white;
            }

            h5{
                margin-top: 7.5px;
                font-size: 1rem;
            }
        }

        &:hover .text-hover{
            display: flex;
        }
    }

    .ms_main-card-txt{
        padding: 1rem;


        button{
            color: white;
            background-color: $mainOrangeColor;
            border-radius: 0;
        }
    }

    &:hover img{
        transform: scale(1.05);
    }
    
    h5{
        font-size: 1.35rem;
    }

    pre{
        font-size: 0.8rem
    };
    
}

.ms_img-container{
    
    position: relative;
    flex-basis: 50%;
    margin-bottom: 16px;
    text-align: center;
    overflow: hidden;

    img{
        width: 100%;
        transition: transform .5s ease;
    }

    .text-hover{
        position: absolute;
        top: 0%;
        left: 0%;
        height: 100%;
        width: 100%;
        display: none;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 25px;
        color: white;
        background-image: linear-gradient(to top, $mainOrangeColor, #fc742594);

        a{
            width: 35px;
            line-height: 35px;

            display: inline-block;
            border-radius: 50%;
            background-color: white;
        }

        h5{
            margin-top: 7.5px;
            font-size: 1rem;
        }
    }

    &:hover .text-hover{
        display: flex;
    }

    &:hover img{
        transform: scale(1.1);
    }
}
</style>