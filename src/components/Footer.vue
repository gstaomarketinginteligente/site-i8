<template>
  <footer>
    <div class="main-section">
      <div class="footer-container">
        <img
          src="../assets/images/footer/logo-footer.svg"
          alt="logo rodape i8"
        />
        <div class="about-section">
          <p class="section-title">Sobre a i8</p>
          <div>
            <a href="#">Quem Somos</a>
            <a href="#">Nossos Cases</a>
            <a href="#">Clientes</a>
            <a href="#">Soluções</a>
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
            <img src="../assets/images/footer/phone.svg" alt="telefone icone" />
            <a href="tel:+5548988186998">+55 48 98818-6998</a>
          </div>
          <div>
            <img src="../assets/images/footer/email.svg" alt="carta icone" />
            <a href="mailto:marketing@i8.com.br">marketing@i8.com.br </a>
          </div>
        </div>
        <div class="social-section">
          <p class="section-title">Redes Sociais</p>
          <div>
            <img src="../assets/images/footer/facebook.svg" alt="facebook i8" />
            <img
              src="../assets/images/footer/instagram.svg"
              alt="instagram i8"
            />
            <img src="../assets/images/footer/linkedin.svg" alt="linkedin i8" />
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

<style scoped>
footer {
  color: white;
}

footer p {
  white-space: nowrap;
}

footer a {
  font-size: 1.8rem;
  color: white;
  white-space: nowrap;
}

footer .main-section .footer-container .contact-section a,
footer .main-section .footer-container .social-section a{
  margin-left: 2rem;
}

footer .section-title {
  font-weight: 600;
  font-size: 2.4rem;
  color: var(--verde-escuro);
}

.footer-container {
  max-width: 1366px;
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
}
</style>
