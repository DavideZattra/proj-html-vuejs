<template>
  <div id="ms_foodie-journal" class="container">

      <div class="row">

          <div class="col-12 ms_journal-title">
              <h5 class="text-center text-uppercase">foodie journal</h5>
          </div>

          <div class="col-4 ms_journal-cards">
              <img class="img-fluid" src="../assets/img/single-post-img3.jpg" alt="">
              <h5>Food Corner: Top Japanese Restaurants for Sushi</h5>
              <p>By Admin | March 25th, 2019</p>
          </div>

          <div class="col-4 ms_journal-cards">
              <img class="img-fluid" src="../assets/img/fi-roundup.jpg" alt="">
              <h5>Roundup: My New Favourite Recipes for Healthy Living</h5>
              <p>By Admin | March 25th, 2019</p>
          </div>

          <div class="col-4 ms_journal-cards">
              <img class="img-fluid" src="../assets/img/fi-toasts.jpg" alt="">
              <h5>Why These Toast with Tea are My New Favourite</h5>
              <p>By Admin | March 25th, 2019</p>
          </div>

      </div>

  </div>
</template>

<script>
export default {
name : 'FoodieJournal'
}
</script>

<style lang='scss' scoped>
#ms_foodie-journal{
    position: absolute;
    left: 50%;
    bottom: -60%;
    transform: translateX(-50%);

    .row{
        padding: 0 12px;
        background-color: white;

    }

    .ms_journal-title{
        padding-top: 17.5px ; 
        

        h5{
            font-weight: 500;
        }
    }

    .ms_journal-cards{
        
        
        text-align: center;
        
        h5{
            padding: 10px 0;
            font-size: 1rem;
        }
        p{
            font-size: 0.7rem;
            font-weight: 300;
        }
    }
    
    

}
</style>