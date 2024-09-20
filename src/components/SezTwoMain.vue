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
          <div>
            <img class="size" src="/public/img/blog-55.jpg" alt="blog-55">

            <div>
              <p>

              </p>
              <p>

              </p>
            </div>
          </div>
        </div>
        <div class="col-4 px-3">
          <h6 class="text-start">
            RECENT POSTS
          </h6>
          <div>
            <img class="size" src="/public/img/blog-65.jpg" alt="blog-65">

            <div>
              <p>

              </p>
              <p>

              </p>
            </div>
          </div>
        </div>
        <div class="col-4 px-3">
          <h6 class="text-start">
            FEATURED POSTS
          </h6>
          <div>
            <img class="size" src="" alt="">

            <div>
              <p>

              </p>
              <p>

              </p>
            </div>
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
      }
    }
  }
}
}
</style>
