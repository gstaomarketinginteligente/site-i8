<script setup>
import Card from "../components/Card.vue";
</script>

<template>
  <main>
    <section class="main-section">
      <div class="section-container">
        <div>
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
          <a href="#" class="button">QUERO MODERNIZAR MINHA EMPRESA</a>
        </div>
        <div></div>
      </div>
    </section>
    <section class="section2">
      <div class="section-container">
        <div class="window-wrapper">
          <article>
            <div class="search-bar">
              <img src="src\assets\images\home\search.svg" alt="lupa" />
              <h3>Mas afinal, quem é a i8?</h3>
              <img src="src\assets\images\home\close.svg" alt="x" />
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
                src="src\assets\images\home\icon-section-2.png"
                alt="logo i8 verde"
                style="width: 20rem"
                class="icon-green"
              />
            </div>
            <div>
              <h3>i8 Tecnologia da informação</h3>
              <p>Programação e Desenvolvimento web</p>
              <a href="" class="button">Saiba Mais Sobre a i8</a>
            </div>
          </article>
        </div>
      </div>
    </section>
    <section class="section3">
      <div class="section-container">
        <h2>
          <img src="src\assets\images\home\Vector.svg" alt="tag1" /> Resultados
          da i8 <img src="src\assets\images\home\Vector-1.svg" alt="tag2" />
        </h2>
        <div>
          <div>
            <img src="src\assets\images\home\botmax.png" alt="banner botmax" />
            <div class="content">
              <p>
                Utilizando o ‘‘PostgreSQL’’ a i8 aplicou uma solução no maior
                garantindo segurança e otimizando em 40% a velocidade de
                pesquisa no Sistema, foi uma solução impactante a nível de os
                profissionais técnicos da i8 darem palestras apresentando como
                foi o desenvolvimento desta solução.
              </p>
              <a href="" class="button"
                >Saiba Mais
                <img src="src\assets\images\home\east.svg" alt="seta direita"
              /></a>
            </div>
          </div>
          <div>
            <img src="" alt="" style="width: 100%" />
          </div>
        </div>
      </div>
    </section>
    <section class="section4">
      <div class="section-container">
        <div>
          <div>
            <div class="content-header">
              <img src="src\assets\images\home\factory-icon.png" alt="" />
              <h2>Nossas Soluções</h2>
            </div>
            <p>
              Somos especialistas em Desenvolvimento de Softwares, visando
              sempre modernizar sua empresa usando as mais recentes inovações do
              mercado através da nossa Fábrica de Softwares, que é reconhecida
              por sua agilidade na entrega, mas nós nos estendemos também para:
            </p>
          </div>
          <Card
            srcImg="src\assets\images\home\bd-icon.png"
            cardTitle="Gerenciamento de Banco de Dados"
            cardText="Visando sempre melhorar a performance do seu sistema, realizamos migrações e atualizações que tornam seu sistema mais eficiente, o que resulta em um aumento da produtividade e lucratividade da sua empresa."
          />
          <Card
            srcImg="src\assets\images\home\coworking-icon.png"
            cardTitle="Espaços de Coworking"
            cardText="Escritórios com ambientes perfeitos para desenvolvimento profissional de pessoas e empresas, conforto e network casados de forma a proporcionar a melhor experiência de trabalho possível."
          />
        </div>
      </div>
    </section>
    <section class="section5">
      <div class="section-container">
        <div>
          <h2>Entregamos soluções <span>especializadas.</span></h2>
          <p>
            Podendo desenvolver uma do ZERO caso seja necessário, mas temos
            alguns produtos prontos desenvolvidos ao longo da nossa trajetória.
          </p>
          <a href="" class="button">VER TODOS OS SERVIÇOS</a>
        </div>
      </div>
    </section>
    <section class="section6">
      <div class="section-container"></div>
    </section>
  </main>
</template>

<style scoped>
main .main-section {
  height: 100vh;
  background: url(../assets/images/home/main-section-image.jpg) 5vw / cover
    no-repeat;
}

main .main-section .section-container {
  display: grid;
  grid-auto-columns: 1fr 1fr;
  padding-top: 12rem;
}

main .main-section div p {
  margin: 2.5rem 0;
}

/* section 2 */

main .section2 {
  height: 100vh;
}

main .section2 .section-container .window-wrapper {
  border: 3px solid black;
  padding: 10rem 5rem;
  border-radius: 1.5rem;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}

.window-wrapper .search-bar {
  display: flex;
  border: 3px solid black;
  padding: 1rem 2rem;
  border-radius: 4rem;
  justify-content: space-between;
  position: relative;
  margin-bottom: 2rem;
}

.window-wrapper .search-bar h3 {
  position: absolute;
  left: 6rem;
  align-self: center;
}

.window-wrapper .text-wrapper {
  border: 3px solid black;
  border-radius: 1.5rem;
  padding: 3rem 2rem;
}

.window-wrapper .text-wrapper p:not(:last-child) {
  margin-bottom: 1rem;
}

.window-wrapper article:last-child {
  display: grid;
  grid-template-columns: 0.7fr 1fr;
  justify-items: center;
  border: 3px solid black;
  border-radius: 1.5rem;
  padding: 3rem 2rem;
  gap: 1rem;
}

.window-wrapper article:last-child div {
  display: flex;
  flex-direction: column;
  align-content: center;
}

article .icon-green {
  margin-bottom: 2rem;
}

article .criativo {
  border: 3px solid black;
  border-radius: 1.5rem;
  margin-bottom: 2rem;
}

.window-wrapper article .button {
  display: flex;
  justify-content: center;
  width: 100%;
}

/* section 3 */

.section3 {
  height: 100vh;
}

.section3 .section-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.section3 .section-container > div {
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 1rem;
}

.section3 .content {
  border: 3px solid black;
  border-radius: 1.5rem;
  padding: 3rem 2rem;
}

.section3 .content {
  margin-top: 1rem;
}

.section3 .content p {
  margin-bottom: 2rem;
}

.section3 .section-container > div > div:last-child {
  background: url("https://sm.ign.com/t/ign_br/news/m/mega-man-m/mega-man-movie-in-the-works-at-netflix_hbyv.1200.jpg")
    center/cover no-repeat;
  background-size: 120%;
  border: solid white 3px;
  border-radius: 1.5rem;
  height: 90%;
  animation: rainbow 1s infinite linear;
}

@keyframes rainbow {
  from {
    border-top: red 3px solid;
    border-right: rgb(34, 231, 34) 3px solid;
    border-bottom: blue 3px solid;
    border-left: yellow 3px solid;
  }
  25% {
    border-top: yellow 9px solid;
    border-right: red 9px solid;
    border-bottom: rgb(43, 219, 43) 9px solid;
    border-left: blue 9px solid;
  }
  50% {
    border-top: blue 3px solid;
    border-right: yellow 3px solid;
    border-bottom: red 3px solid;
    border-left: rgb(43, 230, 43) 3px solid;
  }

  75% {
    border-top: rgb(48, 236, 48) 9px solid;
    border-right: blue 9px solid;
    border-bottom: yellow 9px solid;
    border-left: red 9px solid;
  }

  to {
    border-top: red 3px solid;
    border-right: rgb(39, 211, 39) 3px solid;
    border-bottom: blue 3px solid;
    border-left: yellow 3px solid;
  }
}

/* section 4 */

.section4 {
  height: 100vh;
}

.section4 .section-container > div {
  display: flex;
  gap: 2rem;
  border: solid black 3px;
  border-radius: 1.5rem;
  padding: 5rem;
}

.section4 .section-container > div > div:first-child {
  width: 500rem;
}

.section4 .section-container > div .content-header {
  display: flex;
  align-items: center;
}

.section4 .section-container > div .content-header img {
  margin-right: 2rem;
}

/* section 5 */

.section5 {
  height: 50vh;
}

.section5 .section-container > div {
  background: url('../assets/images/home/line2.svg') center no-repeat;
  background-position: 59rem;
  display: flex;
  align-items: center;
  border: solid black 3px;
  border-radius: 1.5rem;
  padding: 5rem;
}

.section5 .section-container > div p {
  width: 70rem;
  margin-right: 20rem;
}
</style>