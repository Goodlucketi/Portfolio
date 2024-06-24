<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faBars } from '@fortawesome/free-solid-svg-icons'
</script>

<template>
  <header class="sticky top-0 z-10">
    <nav class="p-5 bg-slate-900 text-white flex justify-between items-center">
      <div class="logo">
        <h2 class="p-1 font-mono text-xl">Mfoniso Fabian</h2>
      </div>
      <div class="links hidden md:block">
        <router-link to="/" class="mx-4">Home</router-link>
        <router-link to="/" class="mx-4">About</router-link>
        <router-link to="/" class="mx-4">Projects</router-link>
        <router-link to="/" class="mx-4">Skills</router-link>
        <router-link to="/" class="mx-4">Contact</router-link>
      </div>
      <div class="menuBar md:hidden">
        <FontAwesomeIcon :icon="faBars"/>
      </div>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
