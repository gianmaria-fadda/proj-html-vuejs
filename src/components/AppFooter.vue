<script>
export default {
  data() {
    return {
      footerImg: '/public/img/logo-footer.png',
      footerItems: [
        {
          name: 'ABOUT THE VLOG', 
          content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam doloribus sapiente.'
        },
        {
          name: 'RECENT POSTS',
          content: 'Lorem ipsum dolor sit, amet consectetur adipisicing.',
          time: '12:53 AM Dec 19th.',
          img: ['/img/our-office-4-square.jpg', '/img/our-office-5-square.jpg'],
          link: '#'
        },
        {
          name: 'RECENT COMMENTS',
          content: 'Lorem ipsum dolor sit amet.',
          link: '#'
        },
        {
          name: 'CATEGORIES',
          categories: [
            'GADGETS', 'PHOTOGRAPHY', 'LIFESTYLE', 'FASHION', 'RECIPES',
            'TRAVEL', 'BUSINESS', 'ARCHITECTURE', 'REVIEWS', 'SPORTS', 
            'VIDEOS', 'TECHNOLOGY', 'DESIGN'
          ],
          link: '#'
        },
        { name: 'FAQ\'s' },
        { name: 'Sitemap' },
        { name: 'Contact Us' },
      ]
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
            {{ footerItems[0].name }}
          </h6>
          <p v-for="x in 2" class="text-secondary">
            {{ footerItems[0].content }}
          </p>
          <h6 class="text-white mb-4">
            VIEW MORE <span class="fs-5 ps-1">&#8250;</span>
          </h6>
        </div>
        <div class="col-3">
          <h6 class="text-white mb-4">
            {{ footerItems[1].name }}
          </h6>
          <div class="row d-flex mb-3">
            <div class="col-3 px-0">
              <img class="rounded-circle" :src="footerItems[1].img[0]" :alt="footerItems[1].name">
            </div>
            <div class="col px-0 ps-2">
              <p class="text-light">
                {{ footerItems[1].content }}
              </p>
              <p class="text-secondary">
                {{ footerItems[1].time }}
              </p>
            </div>
          </div>
          <div class="row d-flex">
            <div class="col-3 px-0">
              <img class="rounded-circle" :src="footerItems[1].img[1]" :alt="footerItems[1].name">
            </div>
            <div class="col px-0 ps-2">
              <p class="text-light">
                {{ footerItems[1].content }}
              </p>
              <p class="text-secondary">
                {{ footerItems[1].time }}
              </p>
            </div>
          </div>
        </div>
        <div class="col-3">
          <h6 class="text-white mb-4">
            {{ footerItems[2].name }}
          </h6>
          <div>
            <span class="fs-6 text-primary">&#8250;</span>
            <span class="fw-bold text-white mb-0">
              Don Joe
            </span>
            <span class="text-white mb-0">
              commented on 
            </span>
            <span class="fs-6 text-primary">{{ footerItems[2].content }}</span>
            <p class="text-secondary mt-3">
              {{ footerItems[1].time }}
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
            <span class="fs-6 text-primary">{{ footerItems[2].content }}</span>
            <p class="text-secondary mt-3">
              12:53 AM Dec 19th
            </p>
          </div>
        </div>
        <div class="col-2">
          <h6 class="text-white mb-4">
            {{ footerItems[3].name }}
          </h6>
          <div>
            <p v-for="(category, i) in footerItems[3].categories" :key="i" class="bg-black text-white fw-bold rounded-1">{{ category }}</p>
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
              &#8250; {{ footerItems[4].name }}
            </span>
            <span class="text-secondary px-2">
              &#8250; {{ footerItems[5].name }}
            </span>
            <span class="text-secondary px-2">
              &#8250; {{ footerItems[6].name }}
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
