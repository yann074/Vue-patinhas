<script setup>
//import { RouterLink, RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
import HeaderView from './views/HeaderView.vue'
import AtencionView from './views/AtencionView.vue';
import CastrationView from './views/CastrationView.vue'
import PetsView from './views/PetsView.vue' 
import NeuteredView from './views/NeuteredView.vue'
import FooterView from './views/FooterView.vue';
</script>

<template>
  <header>
    <HeaderView />
  </header>

    <AtencionView />
    <CastrationView />
    <PetsView />
    <NeuteredView />

  <footer>
    <FooterView />
  </footer>
</template>

<style>


</style>
