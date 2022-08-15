<template>
  <main id="main">
    <section class="main-section">
      <div class="container">
        <div class="main-content">
          <h1>
            Modernização<br />
            <span>não é o futuro,</span><br />
            é o presente!
          </h1>
          <p>
            Somos a i8 Tecnologia da Informação, uma empresa que auxilia<br />
            outras empresas a modernizar seus sistemas para acabar com o<br />
            desperdício de dinheiro, trazendo soluções diferenciadas, muitas<br />
            vezes consideradas “impossíveis” pela concorrência.
          </p>
          <a href="#form-section" class="button1" style="width: fit-content"
            >QUERO MODERNIZAR MINHA EMPRESA</a
          >
        </div>
        <div></div>
      </div>
    </section>

    <section class="section6" id="form-section">
      <div class="container">
        <div class="form-wrapper">
          <div>
            <h3>
              A hora de modernizar sua empresa já passou… Mas ainda da tempo de
              <span style="color: var(--verde)"
                >recuperar o tempo perdido!</span
              >
            </h3>
            <p>
              Agende agora mesmo uma reunião com nosso especialista, ele irá
              realizar um diagnóstico com você
              <span class="dotted">e apontar pontos chaves</span> que devem ser
              aprimorados!
            </p>
          </div>
          <form id="form">
            <input
              id="formName"
              required
              type="text"
              minlength="5"
              maxlength="30"
              placeholder="Seu Nome:"
            />
            <input
              id="formEmail"
              required
              type="email"
              minlength="6"
              maxlength="30"
              placeholder="Seu Melhor E-mail:"
            />
            <input
              id="formRole"
              required
              type="text"
              minlength="5"
              maxlength="20"
              placeholder="Seu Cargo:"
            />
            <input
              id="formCompany"
              required
              type="text"
              minlength="5"
              maxlength="25"
              placeholder="Nome da Empresa:"
            />
            <input
              id="formNumber"
              required
              type="tel"
              minlength="10"
              maxlength="14"
              placeholder="DDD + Seu Melhor Número:"
            />
            <button class="button1" type="submit" id="formbtn">
              MODERNIZAR MINHA EMPRESA
            </button>
          </form>
        </div>
      </div>
    </section>

    <section class="section2" id="who">
      <div class="container">
        <div class="window-wrapper">
          <article>
            <div class="search-bar">
              <img loading="lazy" src="~/assets/images/search.svg" alt="lupa" />
              <h3 id="type-text">Mas afinal, quem é a i8?</h3>
              <img loading="lazy" src="~/assets/images/close.svg" alt="x" />
            </div>
            <div class="text-wrapper">
              <div>
                <p>
                  A i8 nasceu com o objetivo de trazer soluções inovadoras e
                  diferenciadas para o mercado por meio de softwares,
                  solucionando problemas considerados impossíveis por muitos.
                </p>
                <p>
                  Utilizando todo o conhecimento técnico e a motivação do seu
                  incrível time, a i8 traz para o mercado soluções nunca antes
                  vistas, e ainda em tempo recorde.
                </p>
              </div>
            </div>
          </article>
          <article>
            <div>
              <img
                loading="lazy"
                src="~/assets/images/desktop/home/icon-green-i8.png"
                alt="logo i8 verde"
                style="width: 20rem"
                class="icon-green"
              />
            </div>
            <div>
              <h3>i8 Tecnologia da informação</h3>
              <p>Programação e Desenvolvimento web</p>
              <a href="https://www.i8.com.br/" target="_blank" class="button2">
                Saiba Mais Sobre a i8
                <img
                  src="~/assets/images/east.svg"
                  class="arrow-right"
                  alt=""
                />
              </a>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section3" id="results">
      <div class="container">
        <div class="section-header">
          <img loading="lazy" src="~/assets/images/tagl.svg" alt="tag1" />
          <h2>Resultados da i8</h2>
          <img loading="lazy" src="~/assets/images/tagr.svg" alt="tag2" />
        </div>
        <div>
          <div>
            <img
              class="botmax"
              src="~/assets/images/desktop/home/botmax-banner.png"
              alt="banner botmax"
            />
            <div class="content">
              <p>
                Utilizando o ‘‘PostgreSQL’’ a i8 aplicou uma solução no maior
                garantindo segurança e otimizando em 40% a velocidade de
                pesquisa no Sistema, foi uma solução impactante a nível de os
                profissionais técnicos da i8 darem palestras apresentando como
                foi o desenvolvimento desta solução.
              </p>
              <nuxt-link to="/quem-somos#cases" class="button2"
                >Outros Cases
                <img
                  class="arrow-right"
                  loading="lazy"
                  src="~/assets/images/east.svg"
                  alt="seta direita"
              /></nuxt-link>
            </div>
          </div>
          <div>
            <img
              src="~/assets/images/desktop/home/botmax-data.png"
              alt="Botmax dados"
            />
          </div>
        </div>
      </div>
    </section>

    <section class="section4" id="solutions">
      <div class="container">
        <div>
          <div>
            <div class="content-header">
              <img
                loading="lazy"
                src="~/assets/images/desktop/home/factory-icon.svg"
                alt=""
              />
              <h2>
                <img loading="lazy" src="~/assets/images/tagl.svg" alt="tag1" />
                Nossas Soluções
                <img loading="lazy" src="~/assets/images/tagr.svg" alt="tag2" />
              </h2>
            </div>
            <p>
              Somos especialistas em Desenvolvimento de Softwares, visando
              sempre modernizar sua empresa usando as mais recentes inovações do
              mercado através da nossa Fábrica de Softwares, que é reconhecida
              por sua <span class="dotted">agilidade na entrega,</span>
              mas nós nos estendemos também para:
            </p>
          </div>

          <div class="cards-wrapper">
            <div class="card-wrapper">
              <div class="card-header">
                <img
                  loading="lazy"
                  src="~/assets/images/desktop/home/bd-icon.svg"
                  alt=""
                />
                <p>Gerenciamento de Banco de Dados</p>
              </div>
              <div class="card-content">
                <p>
                  Visando sempre melhorar a performance do seu sistema,
                  realizamos migrações e atualizações que tornam seu sistema
                  mais eficiente, o que resulta em um aumento da produtividade e
                  lucratividade da sua empresa.
                </p>
                <a href="https://www.i8.com.br/" target="_blank" class="button2"
                  >Saiba Mais
                  <img
                    loading="lazy"
                    class="arrow-right"
                    src="~/assets/images/east.svg"
                    alt=""
                /></a>
              </div>
            </div>
            <div class="card-wrapper">
              <div class="card-header">
                <img
                  loading="lazy"
                  src="~/assets/images/desktop/home/coworking-icon.svg"
                  alt=""
                />
                <p>Espaços de Coworking</p>
              </div>
              <div class="card-content">
                <p>
                  Escritórios com ambientes perfeitos para desenvolvimento
                  profissional de pessoas e empresas, conforto e network casados
                  de forma a proporcionar a melhor experiência de trabalho
                  possível.
                </p>
                <a href="https://www.i8.com.br/" target="_blank" class="button2"
                  >Saiba Mais
                  <img
                    loading="lazy"
                    class="arrow-right"
                    src="~/assets/images/east.svg"
                    alt=""
                /></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section5">
      <div class="container">
        <div>
          <div class="section5-header-mobile">
            <h2>Entregamos soluções <span>especializadas.</span></h2>
            <img
              class="section5-close"
              loading="lazy"
              src="~/assets/images/close.svg"
              alt="fechar-icon"
            />
          </div>
          <p>
            Podendo desenvolver uma do <strong>ZERO</strong> caso seja
            necessário, mas temos alguns produtos prontos desenvolvidos ao longo
            da nossa trajetória.
          </p>
          <a href="" class="button2">VER TODOS OS SERVIÇOS</a>
        </div>
      </div>
    </section>

    <section class="sec-partners">
      <div class="container">
        <div class="section-header">
          <img loading="lazy" src="~/assets/images/tagl.svg" alt="tag1" />
          <h2>Nossos Parceiros</h2>
          <img loading="lazy" src="~/assets/images/tagr.svg" alt="tag2" />
        </div>
        <div class="content">
          <div class="partners-wrapper">
            <a href="http://www.acate.com.br/" target="_blank"
              ><img
                class="partner"
                src="~/assets/images/desktop/home/parceiros/acate.png"
                alt=""
            /></a>
            <a href="http://www.acate.com.br/" target="_blank"
              ><img
                class="partner"
                src="~/assets/images/desktop/home/parceiros/midi.png"
                alt=""
            /></a>
            <a href="http://www.sebrae.com.br/" target="_blank"
              ><img
                class="partner"
                src="~/assets/images/desktop/home/parceiros/sebrae.png"
                alt=""
            /></a>
          </div>
        </div>
      </div>
    </section>

    <section class="section6">
      <div class="container">
        <div class="form-wrapper">
          <div>
            <h2>
              A hora de modernizar sua empresa já passou… Mas ainda da tempo de
              <span style="color: var(--verde)"
                >recuperar o tempo perdido!</span
              >
            </h2>
            <p>
              Agende agora mesmo uma reunião com nosso especialista, ele irá
              realizar um diagnóstico com você
              <span class="dotted">e apontar pontos chaves</span> que devem ser
              aprimorados!
            </p>
          </div>
          <form id="form2">
            <input
              id="formName2"
              required
              type="text"
              minlength="5"
              maxlength="30"
              placeholder="Seu Nome:"
            />
            <input
              id="formEmail2"
              required
              type="email"
              minlength="6"
              maxlength="30"
              placeholder="Seu Melhor E-mail:"
            />
            <input
              id="formRole2"
              required
              type="text"
              minlength="5"
              maxlength="20"
              placeholder="Seu Cargo:"
            />
            <input
              id="formCompany2"
              required
              type="text"
              minlength="5"
              maxlength="25"
              placeholder="Nome da Empresa:"
            />
            <input
              id="formNumber2"
              required
              type="tel"
              minlength="10"
              maxlength="14"
              placeholder="DDD + Seu Melhor Número:"
            />
            <button class="button1" type="submit" id="formbtn2">
              MODERNIZAR MINHA EMPRESA
            </button>
          </form>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
import Home from "~/assets/css/home.css";
export default {
  name: "IndexPage",
  head() {
    return {
      title: "Home - i8",
    };
  },
  data() {
    return {};
  },
  mounted() {
    var typeTextId = "#type-text";
    const typeText = document.getElementById("type-text");
    const botmaxImg = document.querySelector(".botmax");
    const sectionHeaders = document.querySelectorAll(".section-header");
    const sectionHeader1 = sectionHeaders[0].children[1];
    const sectionHeader2 = sectionHeaders[1].children[1];
    const windowHeight = window.innerHeight;
    const fullHeight = document.body.clientHeight;

    function fillscrolllineDesktop() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 43) {
        sectionHeader1.style.padding = "0 2rem";
        sectionHeader1.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";

        botmaxImg.style.transform = "translateX(0vw)";
      }

      if (percentScrolled > 80) {
        sectionHeader2.style.padding = "0 2rem";
        sectionHeader2.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }

      if (window.scrollY >= 1000) {
        typeText.style.color = "black";
        new TypeIt(typeTextId, {
          speed: 60,
          loop: false,
        }).go();
        typeTextId = "";
      }
    }

    function fillscrolllineMobile() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 35) {
        sectionHeader1.style.padding = "0 2rem";
        sectionHeader1.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";

        botmaxImg.style.transform = "translateX(0vw)";
      }

      if (percentScrolled > 70) {
        sectionHeader2.style.padding = "0 2rem";
        sectionHeader2.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }

      if (percentScrolled > 24) {
        typeText.style.color = "black";
        new TypeIt(typeTextId, {
          speed: 60,
          loop: false,
        }).go();
        typeTextId = "";
      }
    }

    function fillscrolllineDesktopFullHD() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 43) {
        sectionHeader1.style.padding = "0 2rem";
        sectionHeader1.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";

        botmaxImg.style.transform = "translateX(0vw)";
      }

      if (percentScrolled > 80) {
        sectionHeader2.style.padding = "0 2rem";
        sectionHeader2.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }

      if (window.scrollY >= 1000) {
        typeText.style.color = "black";
        new TypeIt(typeTextId, {
          speed: 60,
          loop: false,
        }).go();
        typeTextId = "";
      }
    }

    if (window.screen.width > 1800) {
      window.addEventListener("scroll", fillscrolllineDesktopFullHD);
    } else if (window.screen.width > 740) {
      window.addEventListener("scroll", fillscrolllineDesktop);
    } else {
      window.addEventListener("scroll", fillscrolllineMobile);
    }

    var dataForm = {
      name: "",
      email: "",
      role: "",
      company: "",
      number: "",
    };

    // Link de compartilhamento do Código.gs da planilha
    var script_url =
      "https://script.google.com/macros/s/AKfycbxm7sCPZtWEnXvICogapEcP0y2-i96zntvdSg2W9UlRBUa10PG6nbtqRbGRfW8-YO8H/exec";
    var emailcheck = false;

    // função para envio dos dados para a planilha
    function insert_value() {
      var name = dataForm.name;
      var email = dataForm.email;
      var number = dataForm.number;
      var role = dataForm.role;
      var company = dataForm.company;

      console.log(name);
      var url =
        script_url +
        "?callback=ctrlq&name=" +
        name +
        "&number=" +
        number +
        "&role=" +
        role +
        "&company=" +
        company +
        "&email=" +
        email +
        "&action=insert";
      var request = jQuery.ajax({
        crossDomain: true,
        url: url,
        method: "GET",
        dataType: "jsonp",
      });
    }

    var formbtn = document.getElementById("formbtn");
    var form = document.getElementById("form");

    form.addEventListener("submit", (event) => {
      const formName = document.getElementById("formName");
      const formEmail = document.getElementById("formEmail");
      const formNumber = document.getElementById("formNumber");
      const formRole = document.getElementById("formRole");
      const formCompany = document.getElementById("formCompany");

      dataForm["name"] = formName.value;
      dataForm["email"] = formEmail.value;
      dataForm["number"] = formNumber.value;
      dataForm["role"] = formRole.value;
      dataForm["company"] = formCompany.value;

      insert_value(); // chamada para a função de inserção de dados

      formbtn.style.pointerEvents = "none";
      formbtn.style.backgroundColor = "lightgray";

      alert(
        "Obrigado pela paciência " +
          dataForm.name +
          ",\nLogo entraremos em contato!"
      );
      location.href = "/obrigado";
      event.preventDefault();
    });

    var formbtn2 = document.getElementById("formbtn2");
    var form2 = document.getElementById("form2");

    form2.addEventListener("submit", (event) => {
      const formName2 = document.getElementById("formName2");
      const formEmail2 = document.getElementById("formEmail2");
      const formNumber2 = document.getElementById("formNumber2");
      const formRole2 = document.getElementById("formRole2");
      const formCompany2 = document.getElementById("formCompany2");

      dataForm["name"] = formName2.value;
      dataForm["email"] = formEmail2.value;
      dataForm["number"] = formNumber2.value;
      dataForm["role"] = formRole2.value;
      dataForm["company"] = formCompany2.value;

      insert_value();

      formbtn2.style.pointerEvents = "none";
      formbtn2.style.backgroundColor = "lightgray";

      alert(
        "Obrigado pela paciência " +
          dataForm.name +
          ",\nLogo entraremos em contato!"
      );

      location.href = "/obrigado";

      event.preventDefault();
    });
  },
};
</script>
