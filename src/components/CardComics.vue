<template>
  <div class="card">
    <img :src="comics.thumb" :alt="comics.series" />
    <h5>{{ comics.series.toUpperCase() }}</h5>
  </div>
</template>

<script>
export default {
  name: "CardComics",
  props: {
    comics: Object,
  },
};
</script>

<style lang="scss" scoped>
.card {
  flex: 0 0 calc(100% / 6);
  color: white;

  img {
    width: 90%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    object-position: 2px 5px;
  }
}
</style>
