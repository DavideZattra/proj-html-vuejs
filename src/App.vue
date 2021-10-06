<template>
  <div id="app">
    <Header :sectionList="sectionList"/>
    <Main />
    <Footer :sectionList="sectionList"/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  },
  data: function(){
    return{
      sectionList: [
        {
          name : 'home',
          url : '#',
          selected : true,
        },
        {
          name : 'recipes',
          url : '#',
          selected : false,
        },
        {
          name : 'places',
          url : '#',
          selected : false,
        },
        {
          name : 'blog',
          url : '#',
          selected : false,
        },
        {
          name : 'about',
          url : '#',
          selected : false,
        },
        {
          name : 'contact',
          url : '#',
          selected : false,
        },
      ]
    }
  }
}
</script>

<style lang="scss">
@import './style/general.scss';
@import './style/variables.scss';
@import "../node_modules/@fortawesome/fontawesome-free/css/all.css";

</style>

