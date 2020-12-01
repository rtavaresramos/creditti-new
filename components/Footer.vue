<template>
  <div class="footer mt-5 d-flex flex-col align-center">
    <div class="contact">
      <div class="social-media d-flex justify-center my-2">
        <a href="https://www.instagram.com/creditti/">
          <i class="fab fa-instagram fa-3x"></i
        ></a>
        <span class="mx-2"></span>
        <a href="https://www.facebook.com/creditti"
          ><i class="fab fa-facebook-f  fa-3x"></i
        ></a>
        <span class="mx-2"></span>
      </div>

      <h4 class="my-2 mt-3 text-center white">ENTRE EM CONTATO</h4>

      <div class="mail d-flex flex-col text-start">
        <a
          class="my-2 d-flex align-center"
          href="https://api.whatsapp.com/send?phone=5585998022720&text=Oi%2C%20quero%20iniciar%20meu%20atendimento!"
        >
          <span><i class="fab fa-whatsapp fa-2x mx-2"></i></span>
          (85) 9.9802-2720
        </a>

        <a
          class="my-2 d-flex align-center"
          href="mailto:contato@creditti.com.br"
        >
          <span><i class="fas fa-envelope fa-2x mx-2"></i></span>
          contato@creditti.com.br
        </a>
      </div>
    </div>
    <div class="logo mt-5">
      <nuxt-link to="/" class="logo">
        <img src="../assets/img/logo-creditti.png" alt="logo" />
      </nuxt-link>
    </div>
    <div>
      <h3>Creditti, CNPJ: 39.540.004/0001-06</h3>
    </div>
    <div class="copy mt-3" style="text-align: center;">
      <cite
        >Developed by
        <a href="https://github.com/rtavaresramos">Rodrigo Tavares Ramos</a> ©
        2020-2020</cite
      >
    </div>
  </div>
</template>

<style lang="css" scoped>
.logo img {
  width: 150px;
}

h3,
a {
  color: #fff;
  font-weight: 500;
  text-align: center;
}

.copy {
  color: #fff;
  font-weight: 200;
  text-align: center;
}

.copy a {
  text-decoration: underline;
}

.footer {
  padding: 40px;
  background: #063860;
}

@media screen and (min-width: 830px) {
  .contact {
    display: none;
  }
}
</style>
