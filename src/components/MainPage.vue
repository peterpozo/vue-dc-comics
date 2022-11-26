<template>
  <main>
    <div class="container">
      <CardComics
        v-for="objComics in Comics"
        :key="objComics.series"
        :comics="objComics"
      />
    </div>
  </main>
</template>

<script>
import CardComics from "@/components/CardComics.vue";
import Comics from "@/components/dc-comics.json";
export default {
  components: {
    CardComics,
  },
  data() {
    return {
      Comics,
    };
  },
};
</script>

<style lang="scss" scoped>
main {
  padding: 4rem 0;
  background-color: #1c1c1c;
}
.container {
  display: flex;
  flex-wrap: wrap;
  margin: 0 auto;
  padding: 0 1rem;
  max-width: 1000px;
}
</style>
