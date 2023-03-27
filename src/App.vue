<style lang="scss">
@use './styles/general.scss';
</style>


<template>
  <TheHeader />
  <main>
    <div class="container py-3">
      <h1 class="text-white">Content Goes Here</h1>
    </div>
  </main>
  <Banner />
  <TheFooter />
</template>

<script>

import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
import Banner from './components/Banner.vue';

export default {
  components: {
    TheHeader,
    TheFooter,
    Banner
  }
}  
</script>



