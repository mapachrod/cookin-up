<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';

export default {
  name: 'App',
  components: { ConteudoPrincipal, Banner }
};
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
</template>

<style scoped>
 
</style>