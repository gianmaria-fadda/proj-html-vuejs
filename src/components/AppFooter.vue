<script>
export default {
  data() {
    return {
    }
  }
}
</script>

<template>
  <footer>
    <div class="container bg-1">
      <div class="row">
        <div class="col-4">
          <h6 class="text-white mb-4">
            ABOUT THE VLOG
          </h6>
          <p class="text-secondary">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laboriosam doloribus sapiente.
          </p>
          <p class="text-secondary">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laboriosam doloribus nemo sapiente...
          </p>
          <h6 class="text-white mb-4">
            VIEW MORE <span class="fs-5 ps-1">&#8250;</span>
          </h6>
        </div>
        <div class="col-3">
          <h6 class="text-white mb-4">
            RECENT POSTS
          </h6>
          <div class="row d-flex mb-3">
            <div class="col-3 px-0">
              <img class="rounded-circle" src="/public/img/our-office-4-square.jpg" alt="our-office-4-square">
            </div>
            <div class="col px-0 ps-2">
              <p class="text-light">
                Lorem ipsum dolor sit, amet consectetur adipisicing.
              </p>
              <p class="text-secondary">
                12:53 AM Dec 19th
              </p>
            </div>
          </div>
          <div class="row d-flex">
            <div class="col-3 px-0">
              <img class="rounded-circle" src="/public/img/our-office-4-square.jpg" alt="our-office-4-square">
            </div>
            <div class="col px-0 ps-2">
              <p class="text-light">
                Lorem ipsum dolor sit, amet consectetur adipisicing.
              </p>
              <p class="text-secondary">
                12:53 AM Dec 19th
              </p>
            </div>
          </div>
        </div>
        <div class="col-3">
          <h6 class="text-white mb-4">
            RECENT COMMENTS
          </h6>
          <div>
            <span class="fs-6 text-primary">&#8250;</span>
            <span class="fw-bold text-white mb-0">
              Don Joe
            </span>
            <span class="text-white mb-0">
              commented on 
            </span>
            <span class="fs-6 text-primary">Lorem ipsum dolor sit amet.</span>
            <p class="text-secondary mt-3">
              12:53 AM Dec 19th
            </p>
          </div>
          <div>
            <span class="fs-6 text-primary">&#8250;</span>
            <span class="fw-bold text-white mb-0">
              Don Joe
            </span>
            <span class="text-white mb-0">
              commented on 
            </span>
            <span class="fs-6 text-primary">Lorem ipsum dolor sit amet.</span>
            <p class="text-secondary mt-3">
              12:53 AM Dec 19th
            </p>
          </div>
        </div>
        <div class="col-2">
          <h6 class="text-white mb-4">
            CATEGORIES
          </h6>
          <div>
            <p class="bg-black text-white fw-bold rounded-1">GADGETS</p>
            <p class="bg-black text-white fw-bold rounded-1">PHOTOGRAPHY</p>
            <p class="bg-black text-white fw-bold rounded-1">LIFESTYLE</p>
            <p class="bg-black text-white fw-bold rounded-1">FASHION</p>
            <p class="bg-black text-white fw-bold rounded-1">RECIPES</p>
            <p class="bg-black text-white fw-bold rounded-1">TRAVEL</p>
            <p class="bg-black text-white fw-bold rounded-1">BUSINESS</p>
            <p class="bg-black text-white fw-bold rounded-1">ARCHITECTURE</p>
            <p class="bg-black text-white fw-bold rounded-1">REVIEVS</p>
            <p class="bg-black text-white fw-bold rounded-1">SPORTS</p>
            <p class="bg-black text-white fw-bold rounded-1">VIDEOS</p>
            <p class="bg-black text-white fw-bold rounded-1">TECHNOLOGY</p>
            <p class="bg-black text-white fw-bold rounded-1">DESIGN</p>
          </div>
        </div>
      </div>
    </div>

    <section>
      <div class="container">
        <div class="row d-flex justify-content-between py-1">
          <div class="col">
            <img class="opacity-50 me-5" src="/public/img/logo-footer.png" alt="logo-footer">
            <span class="text-secondary">&#169; Copyright 2020. All Right Reserved.</span>
          </div>
          <div class="col text-end">
            <span class="text-secondary px-2">
              &#8250; FAQ's
            </span>
            <span class="text-secondary px-2">
              &#8250; Sitemap
            </span>
            <span class="text-secondary px-2">
              &#8250; Contact Us
            </span>
          </div>
        </div>
      </div>
    </section>
  </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

footer {
  background-color: #212529;

  .container {

    padding: 50px 0;
  }
  .col-3 {

    .text-secondary {

      @include font-size-rule;
    }
    .row {

      .col {

        p {


        }
      }
    }
  }

  .col-2 {

    div {
      display: inline-flex;
      flex-wrap: wrap;

      p {
  
        font-size: .6rem;
        margin: 0 4px 5px 4px;
        padding: 5px 10px;
      }
    }
  }
  section {

    background-color: #1C2023;
    .text-secondary {
      @include font-size-rule;

    }
  }
}

// GENERAL

img {
  max-width: 75px;

}
</style>
