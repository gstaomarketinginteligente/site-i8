<template>
  <div>
    <section class="sec-1">
      <div class="container">
        <div class="content">
          <h1>
            Existem infinitas possibilidades do
            <span class="green">impossível se tornar real!</span>
          </h1>
          <p>
            Nosso maior diferencial é a capacidade de
            <strong
              >entender os problemas e propor soluções tecnológicas
              inovadoras.</strong
            >
          </p>
          <p>
            Somos especialistas em desenvolver softwares sob demanda, adaptando
            as necessidades de nosso clientes a um software que
            <strong>solucione seus problemas.</strong>
          </p>
          <p>
            <strong
              >Agende um diagnóstico com nosso especialista, ele irá mapear os
              problemas da sua empresa e apresentar uma solução que pode ser
              desenvolvida.</strong
            >
          </p>
          <a href="https://wa.me/5548988186998" target="_blank" class="button3"
            >Agendar Reunião</a
          >
        </div>
        <div class="bg"></div>
      </div>
    </section>

    <section class="sec-2">
      <div class="container">
        <div class="header-wrapper">
          <div class="section-header">
            <img src="~/assets/images/tagl.svg" alt="" />
            <h2>Conheça nossas <br class="br-mob" />Soluções</h2>
            <img src="~/assets/images/tagr.svg" alt="" />
          </div>
          <p>
            Além de desenvolver soluções do zero, oferecemos como produtos
            outras que já foram desenvolvidas pela i8.
          </p>
        </div>
        <div class="cards-wrapper">
          <div class="card">
            <div class="header">
              <img
                src="~/assets/images/desktop/solutions/cards-icons/icon.svg"
                alt="banco de dados"
              />
              <h3>
                <span class="green">Gerenciamento de Banco de Dados</span>
              </h3>
            </div>
            <div>
              <p>
                Hoje em dia, o banco de dados é o coração da empresa.
                Armazenando todos os dados necessários para dar continuidade na
                atividade empresarial.
              </p>
              <p>
                Ter o seu administrado por profissionais responsáveis e
                experientes possibilita o aumento da produtividade e
                lucratividade, devido a agilidade que pode ser alcançada com um
                SGBD bem estruturado e desenhado.
              </p>
            </div>
          </div>
          <div class="card">
            <div class="header">
              <img
                src="~/assets/images/desktop/solutions/cards-icons/icon-1.svg"
                alt="risk0"
              />
              <h3><span class="green">Risk0</span></h3>
            </div>
            <div>
              <p>
                O Risk0 te proporciona uma integração completa para gerenciar
                riscos em transportes.
              </p>
              <p>
                Ideal para empresas que necessitam de logística avançada, se
                apresenta como uma solução centralizada para monitoramento de
                desempenho.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="sec-3">
      <div class="container">
        <div class="window-wrapper">
          <div class="bg"></div>
          <div class="content">
            <p class="title">Gerenciamento de Banco de Dados</p>
            <h2><span class="green">Para quem é essa solução?</span></h2>
            <p>
              Empresas que estão em fase de grande crescimento e precisam de uma
              <strong>reestruturação do seu banco de dados.</strong>
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="sec-4">
      <div class="container">
        <div class="window-wrapper">
          <div class="content">
            <p class="title">Gerenciamento de Banco de Dados</p>
            <h2><span class="green">Nossa Aplicação</span></h2>
            <p>
              A i8 aplicou uma solução no maior banco de dados jurídico do
              Brasil, garantindo segurança e otimizando em
              <strong>40% a velocidade de pesquisa no Sistema,</strong> foi uma
              solução impactante a nível de os profissionais técnicos da i8 dar
              palestras apresentando como foi desenvolvida tal solução.
            </p>
          </div>
          <div class="bg"></div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: "Soluções - i8",
    };
  },
  mounted() {
    const sectionHeader = document.querySelector(".section-header").children[1];
    const windowHeight = window.innerHeight;
    const fullHeight = document.body.clientHeight;

    function fillscrolllineDesktop() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 20) {
        sectionHeader.style.padding = "0 2rem";
        sectionHeader.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }
    }

    function fillscrolllineMobile() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 10) {
        sectionHeader.style.padding = "0 2rem";
        sectionHeader.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }
    }

    function fillscrolllineDesktopFullHD() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 20) {
        sectionHeader.style.padding = "0 2rem";
        sectionHeader.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }
    }

    if (window.screen.width > 1800) {
      window.addEventListener("scroll", fillscrolllineDesktopFullHD);
    } else if (window.screen.width > 740) {
      window.addEventListener("scroll", fillscrolllineDesktop);
    } else {
      window.addEventListener("scroll", fillscrolllineMobile);
    }
  },
};
</script>

<style scoped>
.br-mob {
  display: none;
}

.sec-1,
.sec-2,
.sec-3,
.sec-4 {
  display: flex;
  align-items: center;
  padding: 5rem 0;
}

.sec-1 {
  padding: 10rem 0;
}

.sec-1 .container {
  display: grid;
  grid-template-columns: 1fr 0.8fr;
  margin-bottom: 5rem;
}

.sec-1 .bg {
  background: url(~/assets/images/desktop/solutions/ilustra.png) center/40rem
    no-repeat;
}

.sec-1 .content {
  margin-left: 4rem;
}

.sec-1 .content h1 {
  margin-bottom: 2rem;
}

.sec-1 .content p {
  margin-bottom: 1rem;
}

.sec-1 .content .button3 {
  margin-top: 2rem;
}

.sec-2 .container {
  display: flex;
  flex-direction: column;
  gap: 5rem;
}

.sec-2 .cards-wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr;
}

.sec-2 .card {
  border: solid 0.3rem var(--verde);
  border-radius: 1rem;
  padding: 5rem;
  filter: grayscale(1);
  transition: 0.2s;
  cursor: default;
}

.sec-2 .card:hover {
  box-shadow: 0rem 0.4rem 1.5rem 0.5rem rgba(10, 191, 4, 0.25);
  filter: grayscale(0);
}

.sec-2 .card div:last-child p:first-child {
  margin-bottom: 1rem;
}

.sec-2 .card .header {
  display: flex;
  align-items: center;
  column-gap: 1.5rem;
  margin-bottom: 2rem;
}

.title {
  color: white;
  background-color: var(--verde);
  width: fit-content;
  padding: 0 1rem;
  border-radius: 2rem;
}

.sec-3,
.sec-4 {
}

.sec-3 .window-wrapper,
.sec-4 .window-wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr;
  box-sizing: content-box;
  height: 40rem;
}

.sec-4 .window-wrapper {
  padding-left: 10rem;
}

.sec-3 .window-wrapper .content,
.sec-4 .window-wrapper .content {
  margin: auto 0;
}

.sec-3 .bg {
  background: url(~/assets/images/desktop/solutions/grafism.svg) center/40rem
    no-repeat;
}
.sec-4 .bg {
  background: url(~/assets/images/desktop/solutions/frame.svg) center/40rem
    no-repeat;
}

.header-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.header-wrapper p {
  max-width: 75rem;
}

@media screen and (max-width: 710px) {
  .br-mob {
    display: block;
  }

  .sec-1 {
    justify-content: center;
  }
  .sec-1 .container {
    grid-template-columns: none;
    grid-template-rows: 1fr;
    text-align: center;
    margin: 0;
  }

  .sec-1 .content {
    margin: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .sec-2 .cards-wrapper {
    width: 90vw;
  }

  .sec-2 .cards-wrapper .card {
    min-width: 80vw;
  }

  .sec-3 .window-wrapper,
  .sec-4 .window-wrapper {
    grid-template-columns: none;
    grid-template-rows: 1fr 1fr;
    padding: 0;
    border: none;
    text-align: center;
    justify-content: center;
    height: 50rem;
  }

  .title {
    margin: auto;
  }

  .sec-3 .bg {
    background: url(~/assets/images/desktop/solutions/grafism.svg) center/30rem
      no-repeat;
  }
  .sec-4 .bg {
    background: url(~/assets/images/desktop/solutions/frame.svg) center/30rem
      no-repeat;
  }
}
</style>
