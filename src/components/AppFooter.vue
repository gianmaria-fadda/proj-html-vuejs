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
              <img src="/public/img/our-office-4-square.jpg" alt="our-office-4-square">
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
              <img src="/public/img/our-office-4-square.jpg" alt="our-office-4-square">
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
      <div class="row d-flex justify-content-between">
        <div class="col"></div>
        <div class="col"></div>
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
}
}

// GENERAL

img {
  max-width: 75px;
  border-radius: 50%;
}
</style>
