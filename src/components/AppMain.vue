<script>
import SezOneMain from './SezOneMain.vue';
import SezTwoMain from './SezTwoMain.vue';

export default {
  data() {
    return {
    }
  },
  components: {
    SezOneMain,
    SezTwoMain
  }
}
</script>

<template>
  <main>

    <SezOneMain />

    <SezTwoMain />

  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

main {


}
</style>
