<script>
export default {
  data() {
    return {
    }
  }
}
</script>

<template>
  <main>
    <div>
      <div class="container">
        <div class="row d-flex justify-content-center m-0">
          <div class="col-4 px-3">
            <div>
              <img src="/public/img/blog-46.jpg" alt="blog-46">

              <div class="pos-abb">
                <b>
                  PHOTOGRAFY
                </b>
                <p>
                  How To Take Better Concert Pictures in 30 Seconds
                </p>
              </div>
            </div>
          </div>
          <div class="col-4 px-3">
            <div>
              <img src="/public/img/blog-47.jpg" alt="blog-47">

              <div class="pos-abb">
                <b>
                  GADGETS
                </b>
                <p>
                  Gadgets Than Make Your Smarthphone Even Smarter
                </p>
              </div>
            </div>
          </div>
          <div class="col-4 px-3">
            <div>
              <img src="/public/img/blog-48.jpg" alt="blog-48">

              <div class="pos-abb">
                <b>
                  TRAVEL
                </b>
                <p>
                  20 Top-Rated Tourist Attractions in Monhattan
                </p>
              </div>
            </div>
          </div>
          <div class="col-4 px-3">
            <div>
              <img src="/public/img/blog-49.jpg" alt="blog-49">

              <div class="pos-abb">
                <b>
                  LIFESTYLE
                </b>
                <p>
                  The Best Way to Ride a Motorcycle
                </p>
              </div>
            </div>
          </div>
          <div class="col-4 px-3">
            <div>
              <img src="/public/img/blog-50.jpg" alt="blog-50">

              <div class="pos-abb">
                <b>
                  TRAVEL
                </b>
                <p>
                  5 Fun Things to Do at the Beach
                </p>
              </div>
            </div>
          </div>
          <div class="col-4 px-3">
            <div>
              <img src="/public/img/blog-51.jpg" alt="blog-51">

              <div class="pos-abb">
                <b>
                  RECIPES
                </b>
                <p>
                  Amazingly Fresh Fruit And Herb Drink For Summer
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

main {

  div {

    background-color: #F7F7F7;
    padding: 10px 0;
    .container {
  
      .row {
  
        .col-4 {
  
          position: relative;
          img {
  
            max-width: 100%;
            filter: brightness(0.5);
            opacity: .9;
          }

          .pos-abb {

            display: inline-block;
            position: absolute;
            z-index: 1;
            top: 50%;
            left: 25px;
            background-color: rgba(0, 0, 0, 0);
            text-align: start;
            b {
  
              font-size: .6rem;
              color: $whiteColor;
              background-color: $blueColor;
              padding: 5px;
              border-radius: 5px;
            }
  
            p {
  
              font-weight: bold;
              color: $whiteColor;
              width: 75%;
            }
          }
        }
      }
    }
  }
}
</style>
