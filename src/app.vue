<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header class="header-container">
      <nav class="navigator">
        <router-link to="/">home</router-link>
        <router-link to="/about">about</router-link>
        <router-link to="/know-how">know how</router-link>
      </nav>
  </header>
  <main class ="main-container">
    <router-view />
  </main>
  <footer class="footer-container">
      <p>linkedin</p>
      <p>github</p>
  </footer>
</template>

<style>

</style>
