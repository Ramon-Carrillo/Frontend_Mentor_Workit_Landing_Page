<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
</script>

<template>
  <div class="container">
    <Hero class="hero" />
  </div>
</template>

<style lang="css">
.container {
  display: flex;
  justify-content: center;
  width: 100vw;
}
.hero {
  background-color: var(--Purple-900);
}
</style>
