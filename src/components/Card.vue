<template>
  <div class="card-wrapper">
    <div class="card-header">
      <img :src="srcImg" alt="" />
      <p>{{ cardTitle }}</p>
    </div>
    <div class="card-content">
      <p>{{ cardText }}</p>
      <a href="" class="button"
        >Saiba Mais <img src="src\assets\images\home\east.svg" alt=""
      /></a>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    srcImg: String,
    cardTitle: String,
    cardText: String,
  },
};
</script>

<style scoped>
.card-wrapper {
  border: 3px solid black;
  border-radius: 1.5rem;
  padding: 2rem 2rem 5rem;
  min-width: 36rem;
}

.card-wrapper .card-header {
    display: flex;
    align-items: center;
    margin-bottom: 2rem;
}

.card-wrapper .card-header img {
    margin-right: 1.5rem;
}

.card-wrapper .card-header p {
    color: var(--verde);
    font-size: 2.4rem;
    font-weight: 600;
}

.card-wrapper .card-content p {
    margin-bottom: 2rem;
}

</style>