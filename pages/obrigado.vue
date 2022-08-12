<template>
  <div>
    <main class="thanks">
      <div class="container">
        <div class="thanks-content">
          <h1>
            MUITO BEM,VOCÊ PERCEBEU QUE CHEGOU A HORA DE
            <span class="green">MODERNIZAR A SUA EMPRESA!</span>
          </h1>
          <div>
            <p>
              Nós iremos ser seus parceiros nessa trajetória, que o destino é
              sua empresa com
              <strong
                >processos automatizados e aprimorados que resultam em mais
                dinheiro no seu bolso.</strong
              >
            </p>

            <p>
              Enviamos um e-mail com mais detalhes para você, é de extrema
              importância que você abra a sua caixa de entrada e leia esse
              e-mail agora mesmo.
            </p>
          </div>
        </div>
        <div class="thanks-bg"></div>
      </div>
    </main>

    <section class="section5">
      <div class="container">
        <div>
          <div class="section5-header-mobile">
            <h2>Acompanhe a i8 <span class="green">no Instagram!</span></h2>
            <img
              class="section5-close"
              loading="lazy"
              src="~/assets/images/close.svg"
              alt="fechar-icon"
            />
          </div>
          <p>
            Perfeito, agora que você leu e respondeu o e-mail, se você quiser
            acompanhar nosso instagram, lá tem diversos conteúdos que irão te
            auxiliar a entender como a nossa solução funciona e como será
            aplicada.
          </p>
          <a
            href="https://www.instagram.com/i8tic/?hl=en"
            target="_blank"
            class="button2"
            >NOSSO INSTAGRAM</a
          >
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.thanks {
  background: url(~/assets/images/desktop/thanks/image_box.png) center/cover
    no-repeat;
  background-position-x: 10rem;
}

.thanks .container {
  height: 100vh;
  display: grid;
  grid-template-columns: 1fr 0.9fr;

  align-items: center;
}

.thanks .thanks-content h1 {
  width: 85rem;
  margin-bottom: 2rem;
}

.thanks .thanks-content p {
  font-size: 2rem;
  max-width: 55rem;
}

.thanks-bg {
}

.section5 {
  height: 30vh;
  display: flow-root;
}

.section5 .container > div {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  border: solid black 3px;
  border-radius: 1.5rem;
  padding: 2rem 10rem;
  gap: 5rem;
}

.section5 .container > div::before {
  content: "";
  display: block;
  position: absolute;
  z-index: -1;
  width: 100%;
  height: 100%;
  background: url("~/assets/images/desktop/home/lil-line.svg") center/cover
    no-repeat;
  opacity: 0.2;
}

.section5 .container > div p {
  width: 80%;
}
.section5 .container > div h2 {
  font-size: 3rem;
  line-height: normal;
}

.section5 .button {
  white-space: nowrap;
  border: black 0.4rem solid;
  color: black;
}

.section5-close {
  display: block;
  position: absolute;
  top: 1rem;
  right: 1rem;
  width: 2rem;
}

@media screen and (max-width: 1083px) {
  .thanks {
    background: none;
  }

  .thanks-bg {
    /* background: url(./assets/images/thanks/image_box_mobile.png) center/cover no-repeat; */
    background-position-y: top;
    height: 100%;
    background-image: linear-gradient(
        to bottom,
        rgba(251, 245, 252, 0) 80%,
        rgb(252, 252, 252)
      ),
      url(~/assets/images/desktop/thanks/image_box_mobile.png);
    background-position: center top;
    background-repeat: no-repeat;
    background-size: cover;
  }

  .thanks-bg::after {
    content: "fgdfd";
    width: 100rem;
    height: 100rem;
    background-color: aqua;
  }

  .thanks .container {
    display: grid;
    grid-template-columns: none;
    grid-template-rows: 1fr 0.7fr;
    height: 100vh;

    align-items: center;
  }

  .thanks-content {
    order: 1;
    text-align: center;
  }

  .thanks .thanks-content h1 {
    width: 100%;
    font-size: 4rem;
  }

  .thanks .thanks-content p {
    max-width: 100%;
  }

  .section5-close {
    display: block;
  }

  .section5 {
    min-height: 30rem;
    display: flex;
  }

  .section5 .container > div {
    flex-direction: column;
    gap: 0;
    padding: 0 0 2rem 0;
  }

  .section5 .container > div::before {
    content: none;
  }

  .section5 .container > div p {
    width: 100%;
  }

  .section5-header-mobile {
    display: flex;
    justify-content: space-between;
    border-bottom: 3px black solid;
    width: 100%;
    padding: 1rem 3rem;
  }

  .section5-header-mobile + p {
    padding: 1rem 3rem;
  }

  .section6 {
    /* min-height: 75rem; */
  }
}
</style>
