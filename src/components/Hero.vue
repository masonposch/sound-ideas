<template>
  <div class="hero">
      <div class="bg-image">
        <div class="hero-content">
            <h1>{{ msg }}</h1>
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
    background: url(./../../src/assets/screenprinting.jpg);
    background-size: cover;
            background-repeat: no-repeat;
            height: 100%;
            background-position: center;
            position: relative;
}
</style>