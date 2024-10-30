<script setup></script>
<template>
  <nav class="navigation">
    <div class="nav-content">
      <img
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/1d7b0ca0c742b524272539d0436daba479a766676603c1741d0017e9c3d935f0?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01"
        alt="Workit Logo"
        class="company-logo" />
      <button class="btn-secondary">
        Apply for access
        <div class="btn-underline"></div>
      </button>
    </div>
  </nav>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Manrope:wght@200..800&display=swap');
.navigation {
  background-color: #24053e;
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: center;
  color: #fff;
  justify-content: center;
  padding: 56px 80px 0;
}

.nav-content {
  display: flex;
  width: 100%;
  max-width: 1120px;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

.company-logo {
  object-fit: contain;
  object-position: center;
  width: 96px;
}

.btn-secondary {
  width: 143px;
  padding: 0;
  background: none;
  border: none;
  cursor: pointer;
  color: #fff;
  font: 700 18px/32px Manrope, -apple-system, Roboto, Helvetica, sans-serif;
}

.btn-secondary span {
  width: 140px;
}

.btn-underline {
  background-color: #44ffa1;
  min-height: 3px;
  width: 100%;
}
</style>
