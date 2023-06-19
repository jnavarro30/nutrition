<script setup lang="ts">
import { onMounted } from 'vue';
import { RouterLink, RouterView } from 'vue-router'

// const key = import.meta.env.VITE_FDC_API_KEY

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
