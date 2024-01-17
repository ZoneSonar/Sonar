<script setup>
  import { 
    RouterView 
  } from 'vue-router';

  import Header 
    from '@/components/globals/Header.vue';
  
  import 
    Footer from '@/components/globals/Footer.vue';
  
</script>

<template>
  <Header></Header>
  <main>
    <RouterView />
  </main>
  <Footer></Footer>
</template>