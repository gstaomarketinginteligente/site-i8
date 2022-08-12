<template>
  <div>
    <div class="window-wrapper">
      <div class="img-wrapper">
        <img
          :src="require('~/assets/images/desktop/who/cards-icons/' + iconsrc)"
          alt=""
          class="card-icon"
        />
      </div>

      <div>
        <h3>
          <span class="green">{{ title }}</span>
        </h3>
        <p>{{ desc }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    iconsrc: String,
    title: String,
    desc: String,
  },
};
</script>

<style scoped>
.window-wrapper {
  display: flex;
  padding: 3rem;
  gap: 2rem;
  max-width: 60rem;
}

.window-wrapper .img-wrapper {
  border: 0.3rem solid black;
  border-radius: 1rem;
  padding: 2rem;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.15);
  min-height: 14.6rem;
  min-width: 14.6rem;
  display: flex;
  align-content: center;
  justify-content: center;
}
</style>
