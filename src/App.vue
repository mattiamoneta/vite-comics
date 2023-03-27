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
  <TheFooter />
</template>

<script>

import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';

export default {
  components: {
    TheHeader,
    TheFooter
  }
}  
</script>



