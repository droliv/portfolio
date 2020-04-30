<template>
  <section id="services" class="container-fluid padding">
    <h2>O que eu faço</h2>
    <div class="row service">
      <div class="col-lg-4 col-md-3 col-12">
        <div class="item">
          <i class="fa fa-desktop" aria-hidden="true"></i>
          <h5>Desenvolvimento web</h5>
          <p>Sites e sistemas responsivos e otimizados que se adaptam a qualquer tipo de tela.</p>
        </div>
      </div>
      <div class="col-lg-4 col-md-3 col-12">
        <div class="item">
          <i class="fa fa-shopping-cart" aria-hidden="true"></i>
          <h5>E-commerce</h5>
          <p>Desenvolvimento de lojas virtuais e integração com meios de pagamento online.</p>
        </div>
      </div>
      <div class="col-lg-4 col-md-3 col-12">
        <div class="item">
          <i class="fa fa-comments" aria-hidden="true"></i>
           <h5>Social media</h5>
          <p>Integração com midias sociais para melhorar a comunicação com o cliente.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
#services {
  width: 100%;
}
.service {
  text-align: center;
  /* -webkit-box-shadow: 0px 4px 27px -6px rgba(0, 0, 0, 1);
  -moz-box-shadow: 0px 4px 27px -6px rgba(0, 0, 0, 1);
  box-shadow: 0px 4px 27px -6px rgba(0, 0, 0, 1); */
}
.fa {
  font-size: 50px;
  color: white;
  margin: 5px;
}
.item {
  text-align: center;
  align-items: center;
  align-content: center;
  background: #45c667;
  color: #f9f9f9;
  padding: 20px;
  margin-top: 20px;
  height: 200px;
}
.service p {
  font-size: 18px;
}
</style>