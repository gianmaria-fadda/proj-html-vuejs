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
        <div class="col-4 px-3">
          <h6 class="text-start">
            POPULAR POSTS
          </h6>
          <div class="py-2">
            <img class="size" src="/public/img/blog-55.jpg" alt="blog-55">

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
            <img class="size" src="/public/img/blog-56.jpg" alt="blog-56">

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
            <img class="size" src="/public/img/blog-57.jpg" alt="blog-57">

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
            <img class="size" src="/public/img/blog-58.jpg" alt="blog-58">

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
            <img class="size" src="/public/img/blog-59.jpg" alt="blog-59">

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
        <div class="col-4 px-3">
          <h6 class="text-start">
            RECENT POSTS
          </h6>
          <div class="py-2">
            <img class="size" src="/public/img/blog-65.jpg" alt="blog-65">

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
            <img class="size" src="/public/img/blog-66 (1).jpg" alt="blog-66">

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
            <img class="size" src="/public/img/blog-67.jpg" alt="blog-67">

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
            <img class="size" src="/public/img/blog-68.jpg" alt="blog-68">

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
            <img class="size" src="/public/img/blog-69.jpg" alt="blog-69">

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
        <div class="col-4 px-3">
          <h6 class="text-start">
            FEATURED POSTS
          </h6>
          <div>
            <img class="size" src="" alt="">

            <section>
              <p>

              </p>
              <p>

              </p>
            </section>
          </div>
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
      .size {

        width: 50px;
        height: 50px;
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
    }
  }
}
}
</style>
