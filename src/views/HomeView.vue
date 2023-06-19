<script setup lang="ts"></script>

<template>
  <header class="options">
    <form>
      <input type="text" id="search" placeholder="Search..." />
      <select id="sort">
        <option value="asc">Price Ascending</option>
        <option value="desc">Price Descending</option>
      </select>
      <button type="submit">Search</button>
    </form>
  </header>
  <main class="home">Food Gallery</main>
</template>

<style>
.options {
  display: flex;
  justify-content: space-around;
  padding: 0.5rem;
}

input {
  margin: 0.6rem;
}

.home {
  border: 2px solid red;
}
</style>
