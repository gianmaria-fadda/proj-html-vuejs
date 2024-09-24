<script>
/* 
  Per importare ed utilizzare un componente dentro un altro devo SEMPRE seguire questi 3 passi:
  1) Importazione del componente
  2) Dichiarazione del componente
  3) Utilizzo del componente
*/
// 1) Importazione del componente
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data() {
    return {
      headerImg: '/public/img/logo-default-slim.png',
      headerItemsOne: [
        { name: 'SIGN IN', link: '#' },
        { name: 'ABOUT US', link: '#' },
        { name: 'CONTACT US', link: '#' },
        { name: 'BUY NOW', link: '#' }
      ],
      headerItemsTwo: [
        { name: 'HOME', link: '#' },
        { name: 'ELEMENTS', link: '#' },
        { name: 'FEATURES', link: '#' },
        { name: 'PAGES', link: '#' },
        { name: 'PORTFOLIO', link: '#' },
        { name: 'BLOG', link: '#' },
        { name: 'SHOP', link: '#' }
      ],
      footerImg: '/public/img/logo-footer.png',
      footerItems: [
        {
          name: 'ABOUT THE VLOG', 
          content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam doloribus sapiente.'
        },
        {
          name: 'RECENT POSTS',
          content: 'Lorem ipsum dolor sit, amet consectetur adipisicing.',
          time: '12:53 AM Dec 19th.',
          img: ['/img/our-office-4-square.jpg', '/img/our-office-5-square.jpg'],
          link: '#'
        },
        {
          name: 'RECENT COMMENTS',
          content: 'Lorem ipsum dolor sit amet.',
          link: '#'
        },
        {
          name: 'CATEGORIES',
          categories: [
            'GADGETS', 'PHOTOGRAPHY', 'LIFESTYLE', 'FASHION', 'RECIPES',
            'TRAVEL', 'BUSINESS', 'ARCHITECTURE', 'REVIEWS', 'SPORTS', 
            'VIDEOS', 'TECHNOLOGY', 'DESIGN'
          ],
          link: '#'
        },
        { name: 'FAQ\'s' },
        { name: 'Sitemap' },
        { name: 'Contact Us' },
      ]
    };
  },
  // 2) Dichiarazione del componente
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  methods: {
  }
}
</script>

<template>
    <!-- 3) Utilizzo del componente -->
    <AppHeader :menu-items="headerItems" :header-img="headerImg" />

    <AppMain />

    <AppFooter :menu-items="footerItems" :footer-img="footerImg" />

</template>

<style lang="scss">
@use 'assets/scss/main' as *;
// Import all of Bootstrap's CSS
@import "bootstrap/scss/bootstrap";
</style>
