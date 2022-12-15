<template>
    <div>
      <section class="sec-1">
        <div class="container">
          <div class="content">
            <h1><span class="green">Saiba Mais Sobre a i8</span></h1>
            <div>
              <p>
                Especialistas em modernizar empresas, solucionar os problemas das
                empresas relacionados a otimização de processos, com base em
                criação de tecnologias, para assim facilitar a escala e entrega de
                resultado dos clientes parceiros.
              </p>
              <p>
                Buscando sempre as soluções mais inovadoras possíveis para seus
                clientes, diversas vezes a i8 realizou coisas consideradas
                ‘impossíveis’ pela concorrência.
                <strong>Afinal nunca deixamos alguém nós dizer que não somos capazes de
                  fazer algo!</strong>
              </p>
            </div>
          </div>
          <div></div>
        </div>
      </section>

      <section class="sec-2">
        <div class="container">
          <div class="window-wrapper">
            <div class="bg"></div>
            <div class="content">
              <h2><span class="green">Quem somos?</span></h2>
              <p>
                Uma empresa movida pela inovação, que está sempre atrás de trazer
                coisas novas e realizar o que nunca foi feito antes.
              </p>
              <p>
                A i8 percebeu que no mercado de softwares, existem diversas coisas
                ditas impossíveis pelos técnicos. Porém esse é um mercado que tem
                inovações diárias, o que isso significa?
              </p>
              <p>
                Que algo que foi desenvolvido hoje, pode tornar possível algo que
                até ontem era impossível, então se você tiver disposição de ir
                atrás das inovações e até mesmo desenvolver as próprias,
                <span class="dotted">NÃO EXISTE NADA IMPOSSÍVEL!</span>
              </p>
              <p>
                Essa é a i8, assim somos nós, fundadores e colaboradores que são
                movidos por desafios e não suportam ouvir a frase: ‘isso é
                impossível!’
              </p>
            </div>
          </div>
        </div>
      </section>

      <section class="sec-3">
        <div class="container">
          <div class="window-wrapper">
            <div class="content">
              <h2><span class="green">O que fazemos?</span></h2>
              <p>
                Estamos sempre trazendo soluções modernas na área da Tecnologia da
                Informação, através de
                <strong>produtos fáceis de serem utilizados</strong> e que geram
                <strong>grande valor para nossos clientes</strong> corporativos do
                setor privado.
              </p>
              <p>
                Essas soluções geram agilidade nos processos, aumento na
                velocidade do processamento dos sistemas, integrações entre
                ferramentas e diversos outros aprimoramentos técnicos que resultam
                em <strong>MAIS DINHEIRO NO SEU BOLSO!</strong>
              </p>
              <p>
                Afinal, sua empresa irá desperdiçar menos tempo, menos dinheiro e
                menos esforço da sua equipe para desempenhar as mesmas funções de
                antes!
              </p>
            </div>
            <div class="bg"></div>
          </div>
        </div>
      </section>

      <section class="sec-4">
        <div class="container">
          <div class="window-wrapper">
            <div class="bg"></div>
            <div class="content">
              <h2><span class="green">Como fazemos?</span></h2>
              <p>
                Ao longo da nossa jornada desenvolvemos uma equipe
                multidisciplinar que abrange todos os pontos necessários para
                desenvolver as melhores soluções do mercado na área em que
                atuamos.
              </p>
              <p>
                Após mapear as dores e gargalos da empresa parceira, começamos um
                processo 360° graus aprimorando todo o processo da empresa.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section class="sec-5">
        <div class="container">
          <div class="header">
            <div class="section-header">
              <img src="~/assets/images/tagl.svg" alt="" />
              <h2>Solução Completa</h2>
              <img src="~/assets/images/tagr.svg" alt="" />
            </div>
            <p>
              Ao desenvolver uma solução completa, a gente passa por
              <span class="green">6 etapas principais:</span>
            </p>
          </div>
          <div class="cards-wrapper">
            <card-vue iconsrc="map-icon.svg" title="1º Mapeamento"
              desc="Cliente nos passa sua necessidade, com essa informação avaliamos o que precisa ser feito e se vale a pena ser feito." />
            <card-vue iconsrc="icon.svg" title="2º Orçamento"
              desc="Passamos um orçamento e o prazo em que desenvolvemos a solução." />
            <card-vue iconsrc="icon-1.svg" title="3º Desenvolvimento"
              desc="Se aprovado, iniciamos o desenvolvimento da ferramenta." />
            <card-vue iconsrc="icon-2.svg" title="4º Alinhamento"
              desc="Acompanhamos o progresso mantendo o cliente por dentro através de curtas reuniões diárias." />
            <card-vue iconsrc="icon-3.svg" title="5º Apresentação"
              desc="Após finalizada, marcamos uma reunião para apresentação e treinamento da ferramenta." />
            <card-vue iconsrc="icon-4.svg" title="6º Problema Resolvido!"
              desc="Estando tudo certo, o cliente realiza o pagamento e pode iniciar o uso da ferramenta!" />
          </div>
        </div>
      </section>

      <section class="sec-6" id="cases">
        <div class="container">
          <div class="header">
            <div class="section-header">
              <img src="~/assets/images/tagl.svg" alt="" />
              <h2>Cases</h2>
              <img src="~/assets/images/tagr.svg" alt="" />
            </div>
            <p>
              Confira algumas empresas que já se
              <span class="green">beneficiaram das soluções da i8</span>
            </p>
          </div>
          <div class="cases-images">
            <img src="~/assets/images/desktop/who/cases/Banner-botmax.png" alt="" />
            <img src="~/assets/images/desktop/who/cases/Banner-diageo.png" alt="" />
            <img src="~/assets/images/desktop/who/cases/Banner-HBC.png" alt="" />
            <img src="~/assets/images/desktop/who/cases/Banner-sipolsc.png" alt="" />
          </div>
        </div>
      </section>
    </div>
</template>

<script>
import Who from "@/assets/css/who.css";
import CardVue from "~/components/Card.vue";
export default {
  head() {
    return {
      title: "Quem Somos - i8",
    };
  },
  components: {
    CardVue,
  },
  mounted() {
    const sectionHeaders = document.querySelectorAll(".section-header");
    const sectionHeader1 = sectionHeaders[0].children[1];
    const sectionHeader2 = sectionHeaders[1].children[1];
    const windowHeight = window.innerHeight;
    const fullHeight = document.body.clientHeight;

    function fillscrolllineDesktop() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 62) {
        sectionHeader1.style.padding = "0 2rem";
        sectionHeader1.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }

      if (percentScrolled > 82) {
        sectionHeader2.style.padding = "0 2rem";
        sectionHeader2.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }
    }

    function fillscrolllineMobile() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 42) {
        sectionHeader1.style.padding = "0 2rem";
        sectionHeader1.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }

      if (percentScrolled > 78) {
        sectionHeader2.style.padding = "0 2rem";
        sectionHeader2.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }
    }

    function fillscrolllineDesktopFullHD() {
      const scrolled = window.scrollY;
      const percentScrolled = (scrolled / (fullHeight - windowHeight)) * 100;

      if (percentScrolled > 62) {
        sectionHeader1.style.padding = "0 2rem";
        sectionHeader1.style.animation =
          "titleSectionW 0.5s ease-out 0s forwards, 0.5s titleSectionO ease-in-out 0.2s forwards";
      }

      if (percentScrolled > 82) {
        sectionHeader2.style.padding = "0 2rem";
        sectionHeader2.style.animation =
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
.header {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  margin-bottom: 5rem;
}

.header p {
  font-weight: 400;
  max-width: 50rem;
}

.header span.green {
  white-space: nowrap;
}

.cards-wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.sec-1 {
  padding: 10rem 0;
  display: grid;
  align-items: center;
  grid-template-columns: 1fr 0.7fr;
  background: url(~/assets/images/desktop/who/background.jpg) center / cover no-repeat;
}

.sec-1 .content {
  margin-bottom: 25rem;
  max-width: 65rem;
}

.sec-1 .content h1 {
  margin-bottom: 2rem;
}

.sec-1 .content p:not(:last-child) {
  margin-bottom: 1rem;
}

.sec-2,
.sec-3,
.sec-4 {
  padding: 5rem 0;
}

.sec-2,
.sec-3,
.sec-4,
.sec-5,
.sec-6 {
  display: flex;
  align-items: center;
}

.sec-2 .window-wrapper,
.sec-3 .window-wrapper,
.sec-4 .window-wrapper {
  height: 60rem;
  display: grid;
  grid-template-columns: 1fr 1fr;
}

.sec-2 .window-wrapper {
  padding: 0;
  padding-right: 5rem;
}

.sec-2 .window-wrapper .content,
.sec-3 .window-wrapper .content,
.sec-4 .window-wrapper .content {
  align-self: center;
}

.sec-2 .content h2,
.sec-3 .content h2,
.sec-4 .content h2 {
  margin-bottom: 2rem;
}

.sec-2 .content p:not(:last-child),
.sec-3 .content p:not(:last-child),
.sec-4 .content p:not(:last-child) {
  margin-bottom: 1rem;
}

.sec-2 .bg {
  background: url(~/assets/images/desktop/who/man-w-glasses.png) center/cover no-repeat;
}

.sec-3 .bg {
  background: url(~/assets/images/desktop/who/man-computer.png) center/38rem no-repeat;
}

.sec-4 .bg {
  background: url(~/assets/images/desktop/who/guys.png) center/38rem no-repeat;
}

.sec-5 {
  padding: 5rem 0;
}

.sec-6 {
  padding: 5rem 0;
}

@media screen and (max-width: 930px) {
  .sec-1 {
    background: none;
    place-content: center;
    grid-template-columns: 1fr;
    text-align: center;
  }

  .sec-1 .content {
    margin: 0;
  }

  .sec-2 .container .window-wrapper,
  .sec-3 .container .window-wrapper,
  .sec-4 .container .window-wrapper {
    grid-template-columns: none;
    grid-template-rows: 1fr 1fr;
    border: none;
    padding: 0;
    text-align: center;
    height: 75rem;
  }

  /* .sec-3 .container .window-wrapper {
    grid-template-rows: 1fr 1fr;
  }
  .sec-4 .container .window-wrapper {
    grid-template-rows: 0.4fr 1fr;
  } */

  .sec-2 .bg {
    background-size: 25rem;
  }

  .sec-3 .bg {
    background-size: 25rem;
  }

  .sec-4 .bg {
    background-size: 25rem;
  }

  .sec-5 {}

  .cases-images img {
    max-width: 40rem;
  }
}
</style>
