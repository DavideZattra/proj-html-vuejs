<template>
  <section id="ms_jumbotron">

    <div id="ms_today-picks" class="text-center">
        <div class="ms_sticker">
            <h5 class="text-white text-uppercase m-0">Today's Pick</h5>
        </div>
        <h1>Food Corner: Top Japanese Restaurants for Sushi</h1>
        <h5>March 25, 2019</h5>
    </div>

      <div id="ms_foodie-journal" class="container">

        <div class="row">

            <div class="col-12 ms_journal-title">
                <h5 class="text-center text-uppercase">foodie journal</h5>
            </div>

                <!-- IT WORKS BUT BROWSER DOESN'T LIKE IMAGES -->
            <!-- <div class="col-4 ms_journal-cards" v-for="(element,index) in foodieJournal" :key="index">
                <div class="journal-img">
                  <img class="img-fluid" :src="element.img" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>{{element.title}}</h5>
                  </div>
                </div>
                <h5>{{element.title}}</h5>
                <p>By {{element.author}} | {{element.date}}</p>
            </div> -->
            <div class="col-4 ms_journal-cards">
                <div class="journal-img">
                  <img class="img-fluid" src="../assets/img/single-post-img3.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>Food Corner: Top Japanese Restaurants for Sushi</h5>
                  </div>
                </div>
                <h5>Food Corner: Top Japanese Restaurants for Sushi</h5>
                <p>By Admin | March 25th, 2019</p>
            </div>

            <div class="col-4 ms_journal-cards">
                <div class="journal-img">
                  <img class="img-fluid" src="../assets/img/fi-roundup.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>Roundup: My New Favourite Recipes for Healthy Living</h5>
                  </div>
                </div>
                <h5>Roundup: My New Favourite Recipes for Healthy Living</h5>
                <p>By Admin | March 25th, 2019</p>
            </div>

            <div class="col-4 ms_journal-cards">
                <div class="journal-img">
                  <img class="img-fluid" src="../assets/img/fi-toasts.jpg" alt="">
                  <div class="text-hover">
                    <a href="#"><i class="fas fa-link"></i></a>
                    <h5>Why These Toast with Tea are My New Favourite</h5>
                  </div>
                </div>
                <h5>Why These Toast with Tea are My New Favourite</h5>
                <p>By Admin | March 25th, 2019</p>
            </div>

        </div>

    </div>
    
  </section>
</template>

<script>
// import TodayPicks from './JumbotronPicks.vue'
// import FoodieJournal from './JumbotronJournal.vue'

export default {
name : 'Jumbotron',
props : ['foodieJournal'],
data : function(){
  return{
    counter : 0
  }
}
}
</script>

<style lang='scss' scoped>
@import '../style/variables.scss';

#ms_jumbotron{
  position: relative;
  height: 475px;
  margin-bottom: 375px;
  background-image: url('../assets/img/single-post-img3.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

  #ms_today-picks{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);

    padding: 25px 25px;
    background-color: white;
    border-radius: 15px;
    .ms_sticker{
        position: absolute;
        top: -10%;
        left: 50%;
        transform: translateX(-50%);

        border-radius: 10px;
        padding: 0 25px;
        background-color: $mainOrangeColor;

        h5{
            font-weight: 700;
            font-size: 0.8em;
            line-height: 40px;
        }
    }
    
  }

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
      .journal-img{
        position: relative;

        .text-hover{
          position: absolute;
          top: 0%;
          left: 0%;
          height: 100%;
          display: none;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          padding: 25px;
          color: white;
          background-image: linear-gradient(to top, $mainOrangeColor, #fc742594);
          a{
            width: 45px;
            line-height: 45px;

            display: inline-block;
            border-radius: 50%;
            background-color: white;
          }
        }
        
      }
      
      &:hover .text-hover{
        display: flex;
      }
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
}
</style>