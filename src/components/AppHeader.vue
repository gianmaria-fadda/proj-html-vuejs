<script>
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
      ]
    }
  }
}
</script>

<template>
  <header>
    <div class="bg">
      <div class="container">
        <div class="row">
          <div class="col-3 pe-0">
            <p class="m-0 p-0 d-inline-block">
              Everithing about Lifestyle, Travel and Gadgets!
            </p>
          </div>
          <div class="col ps-0">
            <a v-for="(link, i) in headerItemsOne" key="i" class="ps-0" href="#">{{ link.name }}</a>
          </div>
        </div>
      </div>
    </div>
    <div class="container py-4">
      <img :src="headerImg" alt="logo-default-slim">
    </div>

    <hr class="text-body-secondary">
    
    <div class="container">
      <div class="row">
        <div class="col pb-3">
          <a v-for="(link, i) in headerItemsTwo" key="i" class="ps-0" href="#">{{ link.name }}</a>
        </div>
        <div class="col text-end">
          <i class="fa-solid fa-magnifying-glass"></i>  
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

header {

  .bg {

    background-color: $blueColor;
    .container {

      .row {
        
        padding: 10px 0;
        .col-3 {

          p {

            color: #C9E6F4;
            @include font-size-rule;
          }
        }

        .col {
          a {

            color: $whiteColor;
            @include text-decoration-none-rule;
            @include font-size-rule;
            padding: 0 10px;
          }
        }
      }
    }
  }

  .container {


    img {

      max-width: 100px;
    }
  }

  .container {


    a {

      @include text-decoration-none-rule;
      padding: 0 15px;
      color: #4A5054;
      font-weight: bold;

      &:first-child {

        color: $blueColor;
      }
    }

    i {

      @include pointer-rule;
    }
  }
}
</style>
