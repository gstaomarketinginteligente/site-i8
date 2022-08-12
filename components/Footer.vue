<template>
  <footer>
    <div class="main-section">
      <div class="footer-container">
        <img
          src="~/assets/images/desktop/footer/logo-negative.svg"
          alt="logo rodape i8"
        />
        <div class="about-section">
          <p class="section-title">Sobre a i8</p>
          <div>
            <nuxt-link to="/quem-somos">Quem Somos</nuxt-link>
            <nuxt-link to="/quem-somos#cases">Nossos Cases</nuxt-link>
            <nuxt-link to="/quem-somos#cases">Clientes</nuxt-link>
            <nuxt-link to="/solucoes">Soluções</nuxt-link>
          </div>
        </div>
        <div class="locate-section">
          <p class="section-title">Localização</p>
          <p>
            Av. Luiz Boiteux Piazza, 1302<br />
            Canasvieiras, Florianópolis - SC<br />
            Cep: 88056-000
          </p>
        </div>
        <div class="contact-section">
          <p class="section-title">Fale Conosco</p>
          <div>
            <img
              src="~/assets/images/desktop/footer/phone.svg"
              alt="telefone icone"
            />
            <a href="https://wa.me/5548988186998" target="_blank"
              >+55 48 98818-6998</a
            >
          </div>
          <div>
            <img
              src="~/assets/images/desktop/footer/email.svg"
              alt="carta icone"
            />
            <a href="mailto:marketing@i8.com.br">marketing@i8.com.br </a>
          </div>
        </div>
        <div class="social-section">
          <p class="section-title">Redes Sociais</p>
          <div>
            <a target="_blank" href="https://www.facebook.com/i8tec/">
              <img
                loading="lazy"
                src="~/assets/images/desktop/footer/facebook.svg"
                alt="facebook i8"
              />
            </a>
            <a target="_blank" href="https://www.instagram.com/i8tic/?hl=en">
              <img
                loading="lazy"
                src="~/assets/images/desktop/footer/instagram.svg"
                alt="instagram i8"
              />
            </a>
            <a
              target="_blank"
              href="https://www.linkedin.com/company/i8-tecnologia-da-informa%C3%A7%C3%A3o-e-comunica%C3%A7%C3%A3o/"
            >
              <img
                loading="lazy"
                src="~/assets/images/desktop/footer/linkedin.svg"
                alt="linkedin i8"
              />
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="bottom-section">
      <div class="footer-container">
        <p>© 2021-2022 i8 Tecnologia da Informação</p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  color: white;
}

footer a {
  font-size: 1.8rem;
  color: white;
  white-space: nowrap;
}

footer .main-section .footer-container .contact-section a {
  margin-left: 2rem;
}

footer .section-title {
  font-weight: 600;
  font-size: 2.4rem;
  color: var(--verde-escuro);
}

.footer-container {
  max-width: 90vw;
  width: 100%;
  margin: 0 auto;
  display: flex;
  justify-content: center;
}

footer .footer-container > img {
  width: 10.9rem;
}

footer .main-section {
  background-color: var(--preto-claro);
}

.main-section .footer-container {
  padding: 5rem 0;
  gap: 5rem;
}

.main-section .footer-container > div > p:not(:last-child),
.main-section .footer-container > div > div:not(:last-child) {
  margin-bottom: 2rem;
}

footer .social-section div {
  display: flex;
  justify-content: space-between;
}

footer .contact-section div {
  display: flex;
}

footer .about-section div {
  display: flex;
  flex-direction: column;
}

footer .about-section div a:not(:first-child) {
  margin-top: 2rem;
}

footer .bottom-section p {
  font-size: 1.3rem;
}

footer .bottom-section {
  background-color: black;
  color: lightgray;
  padding: 1rem;
}

@media screen and (max-width: 1060px) {
  footer .main-section .footer-container {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  footer .main-section .footer-container > div {
    margin-top: 5rem;
  }

  footer .main-section .footer-container > div img {
    width: 4rem;
  }

  footer .social-section div {
    width: 90vw;
    justify-content: space-around;
  }
}
</style>
