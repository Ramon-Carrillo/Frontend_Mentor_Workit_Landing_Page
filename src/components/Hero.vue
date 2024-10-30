<script setup></script>

<template>
  <section class="hero-section">
    <div class="hero-content">
      <h1 class="hero-title">
        Data tailored to your needs.
        <div class="hero-decoration"></div>
      </h1>

      <button class="btn-primary">Learn more</button>
    </div>

    <img
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/e39b44a5c43588d4341e36584c8495a3667b05dfbbd04f8de0456a91bf52df71?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01"
      alt="Decorative element"
      class="hero-image-left" />
    <img
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/689d7e1b8a1579a18c78f82d26e208dbd0fa199024fe65d3cbb56ac7f54aedd9?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01"
      alt="Decorative element"
      class="hero-image-right" />
  </section>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Manrope:wght@200..800&display=swap');
.hero-section {
  background-color: #24053e;
  display: flex;
  width: 100%;
  flex-direction: column;
  text-align: center;
  justify-content: center;
  padding: 56px 80px 296px;
}

.hero-content {
  align-self: center;
  display: flex;
  width: 635px;
  height: 256px;
  max-width: 100%;
  flex-direction: column;
  align-items: center;
}

.hero-title {
  position: relative;
  color: #fff;
  font: 600 80px/80px Fraunces, -apple-system, Roboto, Helvetica, sans-serif;
  margin: 0;
  padding: 0;
  letter-spacing: 0;
}

.btn-primary {
  width: 162px;
  background-color: #44ffa1;
  margin-top: 40px;
  overflow: hidden;
  color: #24053e;
  padding: 12px 32px;
  font: 700 18px/32px Manrope, -apple-system, Roboto, Helvetica, sans-serif;
  border: none;
  cursor: pointer;
}

.hero-decoration {
  background-color: #44ffa1;
  position: absolute;
  z-index: 0;
  min-height: 3px;
  width: 263px;
  max-width: 100%;
  right: 136px;
  top: 80px;
  height: 3px;
}

.hero-image-left {
  aspect-ratio: 1.07;
  object-fit: contain;
  object-position: center;
  position: absolute;
  z-index: 0;
  max-width: 100%;
  left: -26px;
  top: 140px;
  width: 270px;
  height: 215px;
}

.hero-image-right {
  aspect-ratio: 0.96;
  object-fit: contain;
  object-position: center;
  width: 141px;
  position: absolute;
  z-index: 0;
  max-width: 100%;
  right: -5px;
  bottom: 305px;
  height: 112px;
}
</style>
<!-- <template>
  <div class="data-tailored-container">
    <header class="header">
      <nav class="navigation">
        <div class="nav-content">
          <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/1d7b0ca0c742b524272539d0436daba479a766676603c1741d0017e9c3d935f0?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="Company Logo" class="company-logo" />
          <button class="btn-secondary">
            <span>Apply for access</span>
            <div class="btn-underline"></div>
          </button>
        </div>
      </nav>
      <section class="hero-section">
        <div class="hero-content">
          <h1 class="hero-title">Data tailored to your needs.</h1>
          <button class="btn-primary">Learn more</button>
        </div>
        <div class="hero-decoration"></div>
        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/e39b44a5c43588d4341e36584c8495a3667b05dfbbd04f8de0456a91bf52df71?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="Decorative element" class="hero-image-left" />
        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/689d7e1b8a1579a18c78f82d26e208dbd0fa199024fe65d3cbb56ac7f54aedd9?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="Decorative element" class="hero-image-right" />
      </section>
    </header>
    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/b210be92439e25e838a1dc3e2ee345b01430372f5b22700b96e4bdd2d4d10126?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="" class="divider" />
    <section class="illustration-section">
      <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/f72eed844bd9a90dfd47b80179d765bbb4c1996c5e18a36a090aed33bde341f6?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="Data visualization illustration" class="main-illustration" />
    </section>
    <section class="value-proposition">
      <div class="value-content">
        <div class="value-items">
          <ValueItem
            number="1"
            title="Actionable insights"
            description="Optimize your products, improve customer satisfaction and stay ahead of the competition with our product data analytics."
          />
          <ValueItem
            number="2"
            title="Data-driven decisions"
            description="Make data-driven decisions with our product data analytics. Our AI-generated reports help you unlock insights hidden in your product data."
          />
          <ValueItem
            number="3"
            title="Always affordable"
            description="Always affordable pricing that scales with your business. Get top-quality product data analytics services without hidden costs or unexpected fees."
          />
        </div>
      </div>
    </section>
    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/4fed47db3be83094b6744056ebca77739be50fed62a2a9b027503d35031638a7?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="" class="divider" />
    <section class="cta-section">
      <div class="cta-content">
        <div class="headshot-container">
          <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/9ca995ea6fa99f0373aba869451581e4b12732010453ba0a855439b774959a99?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="Louis Graham, company founder" class="founder-image" />
        </div>
        <div class="cta-text-content">
          <h2 class="cta-title">Be the first to test</h2>
          <p class="cta-description">
            Hi, I'm Louis Graham, the founder of the company. Book a demo call with me to become a beta tester for our app and kickstart your company. Apply for access below and I'll be in touch to schedule a call.
          </p>
          <button class="btn-primary">Apply for access</button>
        </div>
      </div>
    </section>
    <footer class="footer">
      <div class="footer-content">
        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/862b09d25d6d1b92fa7a41bd2733f9f0cefe1e90c77c6757ef4210cdf487cebf?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="Company Logo" class="company-logo" />
        <div class="social-links">
          <a href="#" aria-label="Facebook">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/2ee00420ae7b66b08c4fc236659c42ed22e93639c9e62aeb21e95d2205b32c29?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="" class="social-icon" />
          </a>
          <a href="#" aria-label="Twitter">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/70f38b70a89a53025f1ce8f734598d4627840fbdec2ad7858dd826d3214da979?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="" class="social-icon" />
          </a>
          <a href="#" aria-label="Instagram">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/3125d4e29c3f2e1a1a686a286f1c1ba490f60c5e928989d477e96d5ce1349722?placeholderIfAbsent=true&apiKey=cbba8f96b76946f5b885d0cd675f0f01" alt="" class="social-icon" />
          </a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import ValueItem from './ValueItem.vue';

export default {
  name: 'DataTailoredComponent',
  components: {
    ValueItem,
  },
};
</script>

<style scoped>
.data-tailored-container {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  padding: 0 80px;
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

.navigation {
  background-color: #24053e;
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: center;
  color: #fff;
  justify-content: flex-start;
  padding: 56px 80px 0;
  font: 700 18px/32px Manrope, -apple-system, Roboto, Helvetica, sans-serif;
}

.nav-content {
  display: flex;
  width: 100%;
  max-width: 1120px;
  align-items: center;
  gap: 40px 100px;
  justify-content: space-between;
  flex-wrap: wrap;
}

.company-logo {
  aspect-ratio: 3.85;
  object-fit: contain;
  object-position: center;
  width: 96px;
  align-self: stretch;
  margin: auto 0;
}

.btn-secondary {
  align-self: stretch;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  width: 143px;
  margin: auto 0;
  background: none;
  border: none;
  cursor: pointer;
  color: #fff;
  font: inherit;
}

.btn-underline {
  background-color: #44ffa1;
  min-height: 3px;
  width: 100%;
}

.hero-section {
  position: relative;
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: flex-start;
  text-align: center;
  justify-content: center;
  padding: 56px 80px 296px;
}

.hero-content {
  align-self: center;
  position: relative;
  z-index: 1;
  display: flex;
  width: 635px;
  max-width: 100%;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
}

.hero-title {
  color: #fff;
  font: 600 80px/80px Fraunces 144pt, -apple-system, Roboto, Helvetica, sans-serif;
  margin: 0;
}

.btn-primary {
  align-self: stretch;
  background-color: #44ffa1;
  margin-top: 40px;
  gap: 8px;
  overflow: hidden;
  color: #24053e;
  padding: 12px 32px;
  font: 700 18px/32px Manrope, -apple-system, Roboto, Helvetica, sans-serif;
  border: none;
  cursor: pointer;
}

.hero-decoration {
  background-color: #44ffa1;
  position: absolute;
  z-index: 0;
  min-height: 3px;
  width: 243px;
  max-width: 100%;
  right: 150px;
  top: 80px;
  height: 3px;
}

.hero-image-left {
  aspect-ratio: 1.07;
  object-fit: contain;
  object-position: center;
  width: 340px;
  position: absolute;
  z-index: 0;
  max-width: 100%;
  left: -101px;
  top: 47px;
  height: 317px;
}

.hero-image-right {
  aspect-ratio: 0.96;
  object-fit: contain;
  object-position: center;
  width: 173px;
  position: absolute;
  z-index: 0;
  max-width: 100%;
  right: -46px;
  bottom: 176px;
  height: 181px;
}

.divider {
  aspect-ratio: 20;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

.illustration-section {
  align-self: center;
  display: flex;
  width: 767px;
  max-width: 100%;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.main-illustration {
  aspect-ratio: 1.74;
  object-fit: contain;
  object-position: center;
  width: 100%;
  border-radius: 0;
}

.value-proposition {
  background-color: #fcf8ff;
  display: flex;
  width: 100%;
  flex-direction: column;
  text-align: center;
  justify-content: center;
}

.value-content {
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 88px 80px 144px;
}

.value-items {
  display: flex;
  width: 100%;
  max-width: 1120px;
  align-items: flex-start;
  gap: 32px;
  justify-content: flex-start;
  flex-wrap: wrap;
}

.cta-section {
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 112px 80px 0;
}

.cta-content {
  display: flex;
  width: 100%;
  max-width: 1120px;
  justify-content: space-between;
}

.headshot-container {
  display: flex;
  min-width: 240px;
  align-items: flex-start;
  gap: 8px;
  justify-content: flex-end;
  height: 100%;
  width: 477px;
}

.founder-image {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 477px;
  min-width: 240px;
}

.cta-text-content {
  display: flex;
  min-width: 240px;
  padding-top: 168px;
  flex-direction: column;
  align-items: center;
  font-family: Manrope, sans-serif;
  color: #fff;
  line-height: 32px;
  justify-content: flex-end;
  width: 730px;
  background-color: #24053e;
  max-width: 730px;
  padding: 64px;
}

.cta-title {
  font: 600 56px/1.2 Fraunces 144pt, -apple-system, Roboto, Helvetica, sans-serif;
  margin: 0;
}

.cta-description {
  font-size: 18px;
  font-weight: 400;
  margin-top: 32px;
}

.footer {
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 112px 80px;
}

.footer-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.social-links {
  display: flex;
  margin-top: 56px;
  align-items: center;
  gap: 28px;
  justify-content: center;
}

.social-icon {
  width: 20px;
  height: 20px;
}

@media (max-width: 991px) {
  .data-tailored-container {
    padding-left: 20px;
  }

  .header {
    max-width: 100%;
  }

  .navigation {
    max-width: 100%;
    padding: 0 20px;
  }

  .nav-content {
    max-width: 100%;
  }

  .hero-section {
    max-width: 100%;
    padding: 0 20px 100px;
  }

  .hero-title {
    font-size: 40px;
    line-height: 44px;
  }

  .btn-primary {
    padding: 0 20px;
  }

  .divider {
    max-width: 100%;
  }

  .value-content {
    max-width: 100%;
    padding: 0 20px 100px;
  }

  .value-items {
    max-width: 100%;
  }

  .cta-section {
    max-width: 100%;
    padding: 100px 20px 0;
  }

  .cta-content {
    max-width: 100%;
  }

  .headshot-container {
    max-width: 100%;
  }

  .cta-text-content {
    max-width: 100%;
    padding: 0 20px;
  }

  .cta-title {
    font-size: 40px;
  }

  .cta-description {
    max-width: 100%;
  }

  .footer {
    max-width: 100%;
    padding: 100px 20px;
  }
}
</style> -->
