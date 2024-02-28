<script setup>
import AppHero from './components/AppHero.vue'
</script>

<template>
  <div class="jumbotron">
    <div>
      <a href="" target="_blank">
        <img src="/vite.svg" class="logo" alt="Vite logo" />
      </a>
    </div>
    <AppHero msg="La mia prima app con Vite!" />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
</style>
