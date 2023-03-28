<style lang="scss">
@use './styles/general.scss';
</style>


<template>
  <TheHeader />
  <main>
    <div class="container-fluid fs-banner"></div>
    <div class="container-fluid bg-dark">
      <div class="container">
        <CardsStack title="Current Series" />
      </div>
    </div>
  </main>
  <Banner />
  <TheFooter />
</template>

<script>

import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
import Banner from './components/Banner.vue';
import CardsStack from './components/CardsStack.vue';

export default {
  components: {
    TheHeader,
    TheFooter,
    Banner,
    CardsStack
  }
}  
</script>



