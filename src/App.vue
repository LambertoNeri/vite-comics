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

<style>

</style>
