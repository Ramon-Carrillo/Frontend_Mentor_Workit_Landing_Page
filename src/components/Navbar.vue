<template>
  <nav>
    <ul>
      <li>
        <img :src="logo" alt="Workit Logo" />
      </li>
      <li>Apply for access</li>
    </ul>
  </nav>
</template>

<style lang="css">
@import url('https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Manrope:wght@200..800&display=swap');
nav {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  width: 1440px;
  height: 91px;
  padding: 56px 80px 0 80px;
}
ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 1120px;
  height: 35px;
  margin: 0;
  padding: 0;
}
li {
  list-style: none;
  color: white;
  font-size: 18px;
  line-height: 150%;
  font-weight: 800;
  font-family: 'Manrope', sans-serif;
}
li:last-child {
  padding-bottom: 2px;
  border-bottom: 3px solid hsl(150, 100%, 63%);
}
li img {
  width: 95.76px;
  height: 25px;
}
</style>

<script setup>
import logo from '@/assets/images/logo-light.svg'
</script>
