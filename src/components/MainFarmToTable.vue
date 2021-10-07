<template>
  <section id="ms_farmtotable" class="container">
    <div class="row justify-content-center">
      <div class="col-8">
        <h5 class="text-uppercase">Farm to table</h5>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Doloremque, saepe. Tempore officiis cumque velit accusamus.</p>
      </div>
      <div class="col-2 text-end">
        <button class="btn">Read our blog <i class="fas fa-book-reader"></i></button>
      </div>
      <div class="col-8">
        <div class="row">
          <div class="col-12 ms_main-card">
            <img class="img-fluid" src="../assets/img/single-post-img3.jpg" alt="">
            <h5>Food Corner: Top Japanese Restaurants for Sushi</h5>
            <pre>By Admin | March 25th, 2019</pre>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias, maiores perspiciatis nam facere nulla quod neque exercitationem beatae blanditiis officia odio dolorem aliquid inventore nemo quis, dignissimos, sunt earum hic! Et ipsam natus provident consequuntur?</p>
            <p class="d-flex justify-content-between">
              <a href="#">Read More ></a>
              <i class="far fa-comment"> 0</i>
            </p>
          </div>
          <div class="col-5 flex-grow-1 text-center ms_card">
            <img class="img-fluid" src="../assets/img/fi-roundup.jpg" alt="">
            <h5>Roundup: My New Favourite Recipes for Healthy Living</h5>
            <p>By Admin | March 25th, 2019</p>
          </div>
          <div class="col-5 flex-grow-1 text-center ms_card">
            <img class="img-fluid" src="../assets/img/fi-korean-food.jpg" alt="">
            <h5>Meal Prep: Korean Bibimbap with Kimchi</h5>
            <p>By Admin | March 25th, 2019</p>
          </div>
          <div class="col-5 flex-grow-1 text-center ms_card">
            <img class="img-fluid" src="../assets/img/fi-toasts.jpg" alt="">
            <h5>Why These Toast with Tea are My New Favourite</h5>
            <p>By Admin | March 25th, 2019</p>
          </div>
          <div class="col-5 flex-grow-1 text-center ms_card">
            <img class="img-fluid" src="../assets/img/fi-street-food.jpg" alt="">
            <h5>Exploring Street Food in Bangkok</h5>
            <p>By Admin | March 25th, 2019</p>
          </div>
          <div class="col-5 flex-grow-1 text-center ms_card">
            <img class="img-fluid" src="../assets/img/fi-organic-breakfast.jpg" alt="">
            <h5>Organic Choices For Healthier Living</h5>
            <p>By Admin | March 25th, 2019</p>
          </div>
          <div class="col-5 flex-grow-1 text-center ms_card">
            <img class="img-fluid" src="../assets/img/fi-water-side-rest.jpg" alt="">
            <h5>5 Waterside Restaurants in Istanbul for Special Events</h5>
            <p>By Admin | March 25th, 2019</p>
          </div>
          <div class="col-11 text-center text-uppercase">
            Load More Posts
          </div>
        </div>
      </div>
      <aside class="col-3 text-end">
        <div class="row">
          <div class="col-12">
            <img class="img-fluid" src="../assets/img/ad-bg.jpg" alt="">
          </div>
          <div class="col-12">
            <img class="img-fluid" src="../assets/img/singapore-featured-image.jpg" alt="">
            <button class="btn text-uppercase"><i class="fas fa-globe-americas"></i> view all city guides</button>
          </div>
          <hr>
          <div class="col-12">
            <label for=""><i class="fas fa-search"></i></label>
            <input type="text" placeholder="Search...">
          </div>
          <div class="col-12">
            <h5>Follow Us</h5>
            <p>
              <a href="#"><i class="fab fa-facebook"></i></a>
              <a href="#"><i class="fab fa-instagram"></i></a>
              <a href="#"><i class="fab fa-twitter"></i></a>
              <a href="#"><i class="fab fa-youtube"></i></a>
            </p>
          </div>
          <div class="col12 d-flex">

            <button class="btn flex-grow-1">Popular</button>
            <button class="btn flex-grow-1">Recent</button>

          </div>
          <div class="col-12 d-flex ms_popular-recent">
            <img src="../assets/img/single-post-img3.jpg" alt="">
            <div class="ms_text">
              <h5>Food Corner: Top Japanese Restaurants for Sushi</h5>
              <pre>March 25th, 2019</pre>
            </div>
          </div>
          <div class="col-12 d-flex ms_popular-recent">
            <img src="../assets/img/singapore-featured-image.jpg" alt="">
            <div class="ms_text">
              <h5>Food Corner: Top Japanese Restaurants for Sushi</h5>
              <pre>February 27th, 2019</pre>
            </div>
          </div>
          <div class="col-12 d-flex ms_popular-recent">
            <img src="../assets/img/slide1-bg-150x150.jpg" alt="">
            <div class="ms_text">
              <h5>6 Nutritional Tips to Help Burn Body Fat</h5>
              <pre>February 27th, 2019</pre>
            </div>
          </div>
          <div class="col-12 ms_tweet-box">
            <div class="row">
              <div class="col-12 d-flex">
                <h5>Tweets</h5>
                <p class="flex-grow-1">By <a href="#">@Theme_Fusion</a></p>
                <img src="../assets/img/image.svg" alt="">
              </div>
              <div class="col-2">
                <img src="../assets/img/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="">
              </div>
              <div class="col-8">

              </div>
            </div>
          </div>
        </div>
      </aside>
    </div>
  </section>
</template>

<script>
export default {
name: 'farm',
}
</script>

<style lang='scss' scoped>
@import '../style/general.scss';
@import '../style/variables.scss';

button{
  color: white;
  background-color: $mainOrangeColor;
  border-radius: 0;
}

.ms_main-card{
  padding: 0;
  margin: 15px;
  background-color: $mainWhiteColor;
}

.ms_card{
  padding: 0;
  margin: 15px;
  
  background-color: $mainWhiteColor;
}

.ms_popular-recent{
  padding-top: 10px;
  img{
    height: 50px;
    width: 50px;
    border-radius: 50%;
  }
  .ms_text{
    text-align: start;
  }
}

</style>

'<i class="fas fa-search"></i>'