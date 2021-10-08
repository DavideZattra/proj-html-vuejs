<template>
    <div>
        <section id="ms_subscribe" class="text-center">
            <h2>Subscribe <span>&amp;</span> Receive A Free eBook</h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. In exercitationem, sunt saepe dolor quas reprehenderit?</p>
            <input type="text" placeholder="Insert your email...*">
            <button class="btn">Subscribe</button>
            <pre>Lorem ipsum dolor sit amet consectetur adipisicing elit.</pre>
        </section>
        <section class="ms_image-slider">
            <div class="slider-img-container">
                <img src="../assets/img/Yogurt-Nan.jpg" alt="">
            </div>
            <div class="slider-img-container">
                <img src="../assets/img/Mixed-fruits.jpg" alt="">
            </div>
            <div class="slider-img-container">
                <img src="../assets/img/r-rachel-park-366508-unsplash-min.jpg" alt="">
            </div>
            <div class="slider-img-container">
                <img src="../assets/img/r-michelle-tsang-500721-unsplash-min.jpg" alt="">
            </div>

        </section>
    </div>
</template>

<script>
export default {
name : 'Subscribe',
}
</script>

<style lang='scss' scoped>
@import '../style/variables.scss';

#ms_subscribe{
    padding: 75px 0;
    background-color: white;
    background-image: url('../assets/img/subscribe-sec-bg.png');
    background-position: center;
    background-size: cover;

    input{
        padding: 0;
        line-height: 33px;
    }

    button{
        margin-left: 15px;
        color: white;
        text-transform: uppercase;
        background-color: $mainOrangeColor;
        border-radius: 0;
    }
}

.ms_image-slider{
    display: flex;
    .slider-img-container{
        flex-basis: 25%;
        overflow: hidden;
        img{
            width: 100%;
            transition: transform 1s, filter 1s ease-in-out;
            filter: blur(2px);
            transform: scale(1.1)

        }

        img:hover{
        
            filter: blur(0);
            transform: scale(1);
        }
    }

}
</style>