<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav>
  <RouterView />
</template>

<style scoped>
  nav {
    background: red;
    display: flex;
    justify-content: space-around;
  }

  a {
    padding: 1rem;
    color: white;
  }
</style>
