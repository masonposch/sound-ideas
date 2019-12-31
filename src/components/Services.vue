<template>
  <div class="services">
      <div class="service promotional-products">
          <div class="service-content">
              <h2>Promotional products</h2>
          </div>
      </div>
      <div class="service screen-printing">
          <div class="service-content">
              <h2>Screen printing</h2>
          </div>
      </div>
      <div class="service contact">
          <div class="service-content">
              <h2>Contact us</h2>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Services',
  props: {
    msg: String
  }
}
</script>


<style scoped>
#app .services .service {
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
    background-position: center;
    position: relative;
}
#app .services .service.promotional-products {
    background: url(./../../src/assets/shirts.jpg);
}
#app .services .service.screen-printing {
    background: url(./../../src/assets/screenprinting.jpg);
}
#app .services .service.contact {
    background: url(./../../src/assets/shirts-2.jpg);
}
</style>