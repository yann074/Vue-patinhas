<script setup>
//import { RouterLink, RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
import HeaderView from './views/HeaderView.vue'
import AtencionView from './views/AtencionView.vue';
import CastrationView from './views/CastrationView.vue'
</script>

<template>
  <header>
    <HeaderView />
  </header>

  <AtencionView />
  <CastrationView />
  <RouterView />
</template>

<style>


</style>
