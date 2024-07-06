<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faBars } from '@fortawesome/free-solid-svg-icons'

import { ref } from 'vue';
    
    const navActive = ref(false)

    const  toggleNavBar = ()=> {
      console.log('Before toggle:', navActive.value);
        navActive.value = !navActive.value
      console.log('After toggle:', navActive.value);

    }
</script>

<template>
  <header class="sticky top-0 z-10">
    <nav class="p-5 bg-slate-900 text-white flex justify-between items-center relative">
      <div class="logo">
        <h2 class="p-1 font-mono text-xl">Mfoniso Fabian</h2>
      </div>
      <div :class="['links absolute -z-10 md:z-10 top-0 right-0 bg-slate-900/75 md:bg-transparent p-5 pt-24 md:pt-0 h-screen md:h-0 w-8/12 md:relative md:block md:w-4/12',{ hidden:!navActive }]">
        <router-link to="/" class="mx-4 mb-5 block md:inline">Home</router-link>
        <router-link to="/" class="mx-4 mb-5 block md:inline">About</router-link>
        <router-link to="/" class="mx-4 mb-5 block md:inline">Projects</router-link>
        <router-link to="/" class="mx-4 mb-5 block md:inline">Skills</router-link>
        <router-link to="/" class="mx-4 mb-5 block md:inline">Contact</router-link>
      </div>
      <div class="menuBar md:hidden" @click="toggleNavBar">
        <FontAwesomeIcon :icon="faBars"/>
      </div>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
