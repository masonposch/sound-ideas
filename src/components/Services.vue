<template>
  <div class="services">
      <div class="service promotional-products">
          <div class="service-content">
              <h2>Promotional Products</h2>
              <div class="additional">
                    <p>We provide custom promotional products for your business or event.</p>
                    <div class="cta">
                        <a href="https://www.sipromo.com" target="_blank" class="button red">Order Now</a>
                    </div>
              </div>
          </div>
      </div>
      <div class="service screen-printing">
          <div class="service-content">
              <h2>Screen Printing &amp; Embroidery</h2>
              <div class="additional">
                    <p>We provide custom screen printing and embroided apparrel for your business or event.</p>
                    <ul>
                        <li>Minimum order of 100 tshirts</li>
                        <li>No stupid stuff</li>
                    </ul>
                    <div class="cta">
                        <a href="https://www.sipromo.com" target="_blank" class="button red">Order Now</a>
                    </div>
              </div>
          </div>
      </div>
      <div class="service contact">
          <div class="service-content">
              <h2>Have a Question?</h2>
              <div class="additional">
                    <p>Reach out and we'll be in touch shortly.</p>
                    <div class="cta">
                        <a href="tel:6203313825" class="text-link phone"><i class="fa fa-phone"></i> Call (620) 331-3825</a>
                        <a href="mailto:orders@sipromo.com" class="text-link email"><i class="fa fa-envelope"></i> Email us</a>
                    </div>
              </div>
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
    background-position: center;
    position: relative;
    transform-origin: center;
    transition: transform .4s ease-in-out;
}
#app .services .service.promotional-products {
    background-image: url(./../../src/assets/shirts.jpg);
}
#app .services .service.screen-printing {
    background-image: url(./../../src/assets/screenprinting.jpg);
}
#app .services .service.contact {
    background-image: url(./../../src/assets/shirts-2.jpg);
}
</style>