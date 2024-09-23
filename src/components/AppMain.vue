<script>
import SezOneMain from './SezOneMain.vue';
import SezTwoMain from './SezTwoMain.vue';
import SezThreeMain from './SezThreeMain.vue';

export default {
  data() {
    return {
    }
  },
  components: {
    SezOneMain,
    SezTwoMain,
    SezThreeMain
  }
}
</script>

<template>
  <main>

    <SezOneMain />

    <SezTwoMain />

    <SezThreeMain />

  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

</style>
