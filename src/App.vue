<script setup>
import { RouterView } from "vue-router";
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <Header />
  <RouterView />
  <Footer />
</template>

<style>
html {
  --verde: #17bf1f;
  --verde-escuro: #0abf04;
  --roxo: #8366ff;
  --preto-claro: #1a1a1a;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
}

html {
  font-size: 10px;
}

body {
  font-family: "Kanit", sans-serif;
}

img {
  max-width: 100%;
  height: auto;
}

span {
  color: var(--roxo);
}

.section-container {
  max-width: 1366px;
  width: 100%;
  margin: 0 auto;
}

h1 {
  font-size: 6.4rem;
  font-weight: 600;
  line-height: 6.4rem;
}

h2 {
  font-size: 4rem;
  font-weight: 600;
  line-height: 5.98rem;
}

h3 {
  font-size: 2.4rem;
  font-weight: 600;
  line-height: 3.36rem;
}

p {
  font-size: 1.8rem;
  line-height: 2.88rem;
  font-weight: 300;
}

button,
.button {
  font-size: 1.8rem;
  font-weight: 700;
  line-height: 3.24rem;
  padding: 0.5rem 1.5rem;
  border: solid var(--verde) 0.3rem;
  color: var(--verde);
  border-radius: 1.5rem;
  transition: 0.3s;
}

button:hover,
.button:hover {
  filter: brightness(120%);
}

@media screen and (max-width: 1366px) {
  html {
    font-size: 9px;
  }
}

@media screen and (min-width: 1360px) {
  .section-container {
    padding: 0vh 5vw;
  }
}
</style>
