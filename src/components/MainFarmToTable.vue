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
      <aside class="col-2 text-end">
        
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

</style>