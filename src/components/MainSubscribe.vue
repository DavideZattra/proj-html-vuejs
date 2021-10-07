<template>
  <section id="ms_subscribe" class="text-center">
      <h2>Subscribe <span>&amp;</span> Receive A Free eBook</h2>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. In exercitationem, sunt saepe dolor quas reprehenderit?</p>
      <input type="text" placeholder="Insert your email...*">
      <button class="btn">Subscribe</button>
      <pre>Lorem ipsum dolor sit amet consectetur adipisicing elit.</pre>
  </section>
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

</style>