<template>
  <div>
    <HeaderPage />
    <MainPage />
    <FooterPage />
  </div>
</template>

<script>
import HeaderPage from "@/components/HeaderPage.vue";
import MainPage from "@/components/MainPage.vue";
import FooterPage from "@/components/FooterPage.vue";
export default {
  components: {
    HeaderPage,
    MainPage,
    FooterPage,
  },
};
</script>

<style lang="scss" scoped>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  font-family: "Roboto Condensed", sans-serif;
}
@import url("https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300;400;700&display=swap");
</style>
