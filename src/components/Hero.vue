<template>
  <div class="hero">
      <div class="bg-image">
        <div class="hero-content">
            <h1>{{ msg }}</h1>
            <img src="./../assets/sound-ideas-logo-hero.png" alt="Sound Ideas Advertising and Promotion Independence KS logo"/>
            <div class="cta">
              <a href="https://www.sipromo.com/" target="_blank" class="product button">Order Products</a>
              <a href="mailto:orders@sipromo.com/" class="quote button">Get a Quote</a>
            </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<style scoped>
#app .hero .bg-image {
    background: url(./../../src/assets/shirts-2.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
    background-position: center;
    position: relative;
}
</style>