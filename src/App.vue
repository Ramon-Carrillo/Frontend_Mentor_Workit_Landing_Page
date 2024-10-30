<script setup>
import Hero from './components/Hero.vue'
import Navbar from './components/Navbar.vue'
</script>

<template>
  <div class="data-tailored-container">
    <header class="header">
      <Navbar />
      <Hero />
    </header>
  </div>
</template>

<style lang="css" scoped>
.data-tailored-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.header {
  justify-content: center;
  background: #fff;
  display: flex;
  width: 100%;
  max-width: 1440px;
  flex-direction: column;
  overflow: hidden;
}
</style>
