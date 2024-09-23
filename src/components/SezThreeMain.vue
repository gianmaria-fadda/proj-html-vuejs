<script>
export default {
  data() {
    return {
    }
  }
}
</script>

<template>
  <section>
    <div class="container">
      <div class="row d-flex">
        <div class="col-1 btn-left">
          <i class="fa-solid fa-angle-left"></i>
        </div>
        <div class="col">
          <p class="mb-0">
            GADGETS
          </p>
        </div>
        <div class="col">
          <p class="mb-0">
            PHOTOGRAPHY
          </p>
        </div>
        <div class="col">
          <p class="mb-0">
            LIFESTYLE
          </p>
        </div>
        <div class="col">
          <p class="mb-0">
            FASHION
          </p>
        </div>
        <div class="col">
          <p class="mb-0">
            RECIPES
          </p>
        </div>
        <div class="col">
          <p class="mb-0">
            TRAVEL
          </p>
        </div>
        <div class="col-1 btn-right">
          <i class="fa-solid fa-angle-right"></i>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

section {
  background-color: $blueColor;
  padding: 30px 0;

  .container {

    .row {

      .col {
        @include pointer-rule;

        p {
          background-color: #212529;
          color: $whiteColor;
          font-weight: bold;
          padding: 15px 0;

        }
      }

      .col-1 {
        display: flex;
        justify-content: start;
        align-items: center;
        @include pointer-rule;

        &:last-child {

          justify-content: end;
        }
      }
    }
  }
}
</style>
