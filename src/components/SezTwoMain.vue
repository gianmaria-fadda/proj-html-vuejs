<script>
export default {
  data() {
    return {
    }
  }
}
</script>

<template>
  <div class="container">
      <div class="row">
        <div class="col-4 px-3 py-5">
          <h6 class="text-start">
            POPULAR POSTS
          </h6>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-55.jpg" alt="blog-55">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-56.jpg" alt="blog-56">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-57.jpg" alt="blog-57">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-58.jpg" alt="blog-58">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-59.jpg" alt="blog-59">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
        </div>
        <div class="col-4 px-3 py-5">
          <h6 class="text-start">
            RECENT POSTS
          </h6>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-65.jpg" alt="blog-65">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-66 (1).jpg" alt="blog-66">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-67.jpg" alt="blog-67">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-68.jpg" alt="blog-68">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
          <div class="py-2">
            <img class="size-s" src="/public/img/blog-69.jpg" alt="blog-69">

            <section>
              <p>
                Simple Ways to Have a Pretty Face
              </p>
              <p>
                January 12, 2019
              </p>
            </section>
          </div>
        </div>
        <div class="col-4 px-3 py-5">
          <h6 class="text-start">
            FEATURED POSTS
          </h6>
          <div>
            <img class="size-m" src="/public/img/blog-66.jpg" alt="blog-66">

            <div class="pos-abb">
              <b>
                RECIPES
              </b>
              <p>
                Tips to Help You Quickly Prepare your Lunch
              </p>
            </div>
          </div>
          <section class="col py-5">
            <h6 class="text-start">
              FEATURED POSTS
            </h6>
            <div>
              <img src="/public/img/avatar.jpg" alt="avatar">
              <section>
                <p>
                  John Dow
                </p>
                <p>
                  Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                  Corporis eos iste voluptates adipisci, libero dignissimos
                  voluptatum consequuntur.
                </p>
              </section>
            </div>
          </section>
        </div>
      </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.container {

.row {

  .col-4 {

    div {

      display: flex;
      position: relative;
      .size-s {

        width: 50px;
        height: 50px;
      }

      .size-m {

        max-width: 100%;
        filter: brightness(0.5);
        opacity: .9;
      }

      p {

        text-align: start;
        margin: 0;
        padding-left: 10px;

        &:last-child {

          color: grey;
          @include font-size-rule;
        }
      }
      .pos-abb {

        display: inline-block;
        position: absolute;
        z-index: 1;
        top: 50%;
        left: 15px;
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
          width: 88%;
          padding-left: 0;
        }
      }
    }

    .col {

      img {

        max-width: 110px;
        object-fit: contain;
      }

      div {

        section {

          padding-left: 20px;

          p {

            padding: 5px 0;

            &:first-child {

              font-weight: bold;
            }
          }
        }
      }
    }
  }
}
}
</style>
