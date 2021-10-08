<template>
  <div id="app">
    <Header :sectionList="sectionList" />
    <Main :blogArticles="blogArticles" />
    <Footer :sectionList="sectionList" />
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
          url : '#ms_popular-recipes',
          selected : false,
        },
        {
          name : 'places',
          url : '#',
          selected : false,
        },
        {
          name : 'blog',
          url : '#ms_farmtotable',
          selected : false,
        },
        {
          name : 'about',
          url : '#',
          selected : false,
        },
        {
          name : 'contact',
          url : '#ms_upper-footer',
          selected : false,
        },
      ],
      blogArticles : [
        {
          title: 'Food Corner: Top Japanese Restaurants for Sushi',
          img : 'single-post-img3.jpg',
          author : 'Admin',
          date: 'March 25th, 2019',
        },
        {
          title: 'Roundup: My New Favourite Recipes for Healthy Living',
          img : 'fi-roundup.jpg',
          author : 'Admin',
          date: 'March 25th, 2019',
        },
        {
          title: 'Why These Toast with Tea are My New Favourite',
          img : 'fi-toasts.jpg',
          author : 'Admin',
          date: 'March 25th, 2019',
        },
        {
          title : 'Exploring Street Food in Bangkok',
          img : 'fi-street-food.jpg',
          author : 'Admin',
          date : 'March 25th, 2019',
        },
        {
          title : 'Organic Choices For Healthier Living',
          img : 'fi-organic-breakfast.jpg',
          author : 'Admin',
          date : 'March 25th, 2019',
        },
        {
          title : 'Meal Prep: Korean Bibimbap with Kimchi',
          img : 'fi-korean-food.jpg',
          author : 'Admin',
          date : 'March 25th, 2019',
        },
        {
          title : '5 Waterside Restaurants in Istanbul for Special Events',
          img : 'fi-water-side-rest.jpg',
          author : 'Admin',
          date : 'March 25th, 2019',
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

