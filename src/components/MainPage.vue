<template>
  <main>
    <div class="container">
      <CardComics
        v-for="objComics in Comics"
        :key="objComics.series"
        :comics="objComics"
      />
      <button class="button-58" role="button">LOAD MORE</button>
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
  padding: 2rem 0 4rem;
  background-color: #1c1c1c;
}
.container {
  display: flex;
  flex-wrap: wrap;
  margin: 0 auto;
  padding: 0 1rem;
  max-width: 1000px;
}

button {
  // margin: auto;
  // background-color: #0282f9;
  // border: none;
  // padding: 0.4rem 2rem;
  // color: white;
  // font-weight: 600;
  // font-size: 10px;
}
.button-58 {
  margin: auto;
  align-items: center;
  background-color: #0282f9;
  border: 2px solid #0282f9;
  box-sizing: border-box;
  color: #fff;
  cursor: pointer;
  display: inline-flex;
  fill: #000;
  font-family: Inter, sans-serif;
  font-size: 10px;
  font-weight: 600;
  height: 30px;
  justify-content: center;
  letter-spacing: -0.8px;
  line-height: 24px;
  min-width: 140px;
  outline: 0;
  padding: 0 17px;
  text-align: center;
  text-decoration: none;
  transition: all 0.3s;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}

.button-58:focus {
  color: #171e29;
}

.button-58:hover {
  background-color: #3385ff;
  border-color: #3385ff;
  fill: #06f;
}

.button-58:active {
  background-color: #3385ff;
  border-color: #3385ff;
  fill: #06f;
}

@media (min-width: 768px) {
  .button-58 {
    min-width: 170px;
  }
}
</style>
