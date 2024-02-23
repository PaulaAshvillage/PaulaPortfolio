<template>
  <div class="content-wrapper">
    <Header-layout />
  </div>
</template>
<script>
import HeaderLayout from '@/layouts/HeaderLayout.vue'

export default {
  components: {
    HeaderLayout
  }
}
</script>
<style>
@import url('./assets/main.css');
@import url('./assets/base.css');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;600&display=swap');

.content-wrapper {
  margin-inline: auto;
  padding-inline: 1.5rem;
  max-width: 80rem;
}

#app {
  font-family: 'Poppins', Helvetica, sans-serif;
  text-align: center;
}
</style>
