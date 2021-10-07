<template>
  <section id="ms_culinary-collection" class="container">

    <div class="row justify-content-center">
        
        <div class="col-8 text-center">

            <h5>Culinary collection</h5>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati praesentium itaque repellat dignissimos neque soluta.</p>
        </div>
    </div>
    <div class="row justify-content-center P-0">
        <div class="col-3">
            <div class="ms_card">
                <img src="../assets/img/drinks-recipes.png" alt="">
                <p>drinks</p>
            </div>
        </div>
        <div class="col-3">

            <div class="ms_card">
                <img src="../assets/img/soups-recipes.png" alt="">
                <p>soups</p>
            </div>
        </div>
        <div class="col-3">

            <div class="ms_card">
                <img src="../assets/img/baking-recipes.png" alt="">
                <p>bakery</p>
            </div>

        </div>
        <div class="col-3">

            <div class="ms_card">
                <img src="../assets/img/dinner-recipes.png" alt="">
                <p>Dinner</p>
            </div>

        </div>
        <div class="col-3">

            <div class="ms_card">
                <img src="../assets/img/healthy-recipes.png" alt="">
                <p>healthy</p>
            </div>

        </div>
        <div class="col-3">

        <div class="ms_card">
            <img src="../assets/img/staff-picks.png" alt="">
            <p>Staff picks</p>
        </div>

        </div>
        <div class="col-3">
            <div class="ms_card">
                <img src="../assets/img/premium-recipes.png" alt="">
                <p>Appetisers</p>
            </div>
        </div>

        <div class="col-3">

            <div class="ms_card">
                <img src="../assets/img/quick-easy-recipes.png" alt="">
                <p>quick &amp; easy</p>
            </div>
        </div>

        
    </div>

  </section>
</template>

<script>
export default {
name : 'CulinaryCollection',
}
</script>

<style lang='scss' scoped>
@import '../style/variables.scss';

#ms_culinary-collection{
    
    padding-top: 125px;

    .col-3{
        
        margin-bottom: 32px;
    }
    
    .ms_card{
        
        height: 100%;
        background-color: white;
        text-align: center;
        
    
        img{
            padding: 10px 0;
            height: 125px;
        }
    
        p{
            text-transform: uppercase;
        }
    }
}

</style>