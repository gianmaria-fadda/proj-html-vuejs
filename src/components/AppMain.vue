<script>
import SezOneMain from './SezOneMain.vue';
import SezTwoMain from './SezTwoMain.vue';
import SezThreeMain from './SezThreeMain.vue';
import SezFourMain from './SezFourMain.vue';

export default {
  data() {
    return {
    }
  },
  components: {
    SezOneMain,
    SezTwoMain,
    SezThreeMain,
    SezFourMain
  }
}
</script>

<template>
  <main>

    <SezOneMain />

    <SezTwoMain />

    <SezThreeMain />

    <SezFourMain />

  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

</style>
