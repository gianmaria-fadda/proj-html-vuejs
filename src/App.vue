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
      headerItems: [
        { name: 'HOME', 
          link: '#' 
        },
        { name: 'ELEMENTS', 
          link: '#' 
        },
        { name: 'FEATURES', 
          link: '#' 
        },
        { name: 'PAGES', 
          link: '#' 
        },
        { name: 'PORTFOLIO', 
          link: '#' 
        },
        { name: 'BLOG', 
          link: '#'  
        },
        { name: 'SHOP', 
          link: '#' 
        },
      ],
      footerItems: [
        { name: 'ABOUT THE VLOG', 
          content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam doloribus sapiente.', 
          link: '#' 
        },
        { name: 'RECENT POSTS', 
          content: 'Lorem ipsum dolor sit, amet consectetur adipisicing.', 
          link: '#' 
        },
        { name: 'RECENT COMMENTS', 
          content: 'Lorem ipsum dolor sit amet.', 
          link: '#' 
        },
        { name: 'CATEGORIES', 
          categories: ['GADGETS', 
                       'PHOTOGRAPHY', 
                       'LIFESTYLE', 
                       'FASHION', 
                       'RECIPES', 
                       'TRAVEL', 
                       'BUSINESS', 
                       'ARCHITECTURE', 
                       'REVIEWS', 
                       'SPORTS', 
                       'VIDEOS', 
                       'TECHNOLOGY', 
                       'DESIGN'
                      ], 
          link: '#' 
        },
        { name: 'FAQ\'s', 
          link: '#' 
        },
        { name: 'Sitemap', 
          link: '#' 
        },
        { name: 'Contact Us', 
          link: '#' 
        },
      ]
    }
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
    <AppHeader />

    <AppMain />

    <AppFooter />

</template>

<style lang="scss">
@use 'assets/scss/main' as *;
// Import all of Bootstrap's CSS
@import "bootstrap/scss/bootstrap";
</style>
