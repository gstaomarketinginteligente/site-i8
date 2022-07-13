<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <header>
    <div class="main">
      <RouterLink to="/">
        <img src="../assets/images/header/logo-header.svg" alt="logo i8" />
      </RouterLink>
    </div>
    <div class="bottom">
      <ul>
        <li >
          <a href="" v-for="(item, index) in navItems" :key="index">{{ item }}</a>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      navItems: ["O que é a i8", "Resultados", "Nossas Soluções"],
    };
  },
};
</script>

<style scoped>

header {
  width: 100%;
}

header .main {
  border-bottom: 2px black solid;
  padding: 1rem 0;
}

header .bottom {
  background-color: #f1f1f1;
}

header .main,
header .bottom {
  display: flex;
  justify-content: center;
}

ul {
    max-width: 1366px;
    width: 100%;
}

ul li {
  list-style: none;
  display: flex;
  justify-content: space-evenly;
  font-size: 1.8rem;
  width: 100%;
}

</style>