<script>
  import AppFooter from './components/AppFooter.vue';
  import AppHeader from './components/AppHeader.vue';
  import AppProducts from './components/AppProducts.vue';

  export default {
    components: {
      AppHeader,
      AppProducts,
      AppFooter,
    },
  };
</script>


<template>
  <AppHeader></AppHeader>
  <main>
    <AppProducts></AppProducts>
  </main>

  <AppFooter></AppFooter>
</template>

<style lang="scss">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Press Start 2P', cursive;
    font-family: 'Roboto', sans-serif;
  }


</style>

