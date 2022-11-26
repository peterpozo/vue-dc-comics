<template>
  <section class="jumbotron"></section>
</template>

<script>
export default {
  name: "HeaderJumbotron",
  props: {
    jumbotron: Object,
  },
};
</script>

<style lang="scss" scoped>
.jumbotron {
  padding: 15%;
  background-image: url("../img/jumbotron.jpg");
  background-size: cover;
}
</style>
