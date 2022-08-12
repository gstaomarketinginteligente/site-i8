<template>
  <header>
    <div class="container">
      <div class="nav-logo">
        <nuxt-link to="/"
          ><img
            loading="lazy"
            src="~/assets/images/desktop/nav-menu/logo.svg"
            alt="logo i8"
        /></nuxt-link>
      </div>
      <img src="~/assets/images/menu-icon.svg" alt="" class="menu" />
      <div class="nav-items">
        <img src="~/assets/images/close.svg" alt="" class="close" />
        <nuxt-link to="/quem-somos">Quem Somos</nuxt-link>
        <nuxt-link to="/solucoes">Soluções</nuxt-link>
        <a href="https://www.blog.i8.com.br/" target="_blank">Blog</a>
        <a class="button1" href="https://wa.me/5548988186998"
          >Entre em contato</a
        >
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Nav",
  data() {
    return {};
  },
  mounted() {
    const menu = document.querySelector(".menu");
    const close = document.querySelector(".close");
    const navItems = document.querySelector(".nav-items");
    menu.addEventListener("click", () => {
      navItems.style.transform = "translate(0)";
    });
    close.addEventListener("click", () => {
      navItems.style.transform = "translate(70vw)";
    });
  },
};
</script>

<style scoped>
.nav-logo {
  margin-top: 1rem;
}

.close,
.menu {
  display: none;
}

header {
  z-index: 99;
  top: 0;
  background-color: white;
  position: fixed;
  width: 100vw;
  border-bottom: 0.3rem solid gray;
}

header .container {
  justify-content: space-between;
  padding: 1rem 0;
}

header .container,
.nav-items {
  display: flex;
  align-items: center;
}

header img {
  width: 8rem;
}

.nav-items a:not(:last-child) {
  margin-right: 2rem;
}

.nav-items a {
  color: #b8b8b8;
  transition: 0.3s;
}

.nav-items a:hover {
  color: var(--roxo);
  opacity: 0.8;
}

@media screen and (max-width: 600px) {
  .nav-items {
    height: 100vh;
    width: 35rem;
    position: absolute;
    top: 0;
    right: 0;
    flex-direction: column;
    justify-content: center;
    gap: 15rem;
    z-index: 99;
    background-color: white;
    transform: translateX(200vw);
    transition: 0.3s;
  }

  .menu {
    display: block;
    position: absolute;
    top: 1.5rem;
    right: 1.5rem;
    z-index: 98;
    width: 4rem;
    cursor: pointer;
  }

  .close {
    display: block;
    position: absolute;
    top: 1.5rem;
    right: 1.5rem;
    cursor: pointer;
    width: 3.5rem;
  }
}
</style>
