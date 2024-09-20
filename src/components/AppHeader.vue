<script>
export default {
  data() {
    return {
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
            <a class="ps-0" href="#">SIGN IN</a>
            <a href="#">ABOUT US</a>
            <a href="#">CONTACT US</a>
            <a href="#">BUY NOW</a>
          </div>
        </div>
      </div>
    </div>
    <div class="container py-4">
      <img src="/public/img/logo-default-slim.png" alt="logo-default-slim">
    </div>

    <hr class="text-body-secondary">
    
    <div class="container">
      <div class="row">
        <div class="col pb-3">
          <a class="ps-0" href="#">HOME</a>
          <a href="#">ELEMENTS</a>
          <a href="#">FEATURES</a>
          <a href="#">PAGES</a>
          <a href="#">PORTFOLIO</a>
          <a href="#">BLOG</a>
          <a href="#">SHOP</a>
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

            color: white;
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

      cursor: pointer;
    }
  }
}
</style>
