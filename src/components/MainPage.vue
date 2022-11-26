<template>
  <main>
    <div class="container">
      <CardComics v-for="i in 12" :key="i" />
    </div>
  </main>
</template>

<script>
import CardComics from "@/components/CardComics.vue";
export default {
  components: {
    CardComics,
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
