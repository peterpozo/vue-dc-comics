<template>
  <header>
    <section class="header-top">
      <img class="logo" src="../img/dc-logo.png" alt="logo" />
      <nav class="links">
        <li><a href="#!">CHARACTERS</a></li>
        <li><a href="#!">COMICS</a></li>
        <li><a href="#!">MOVIES</a></li>
        <li><a href="#!">TV</a></li>
        <li><a href="#!">GAMES</a></li>
        <li><a href="#!">COLLECTIBLES</a></li>
        <li><a href="#!">VIDEOS</a></li>
        <li><a href="#!">FANS</a></li>
        <li><a href="#!">NEWS</a></li>
        <li><a href="#!">SHOP</a></li>
      </nav>
    </section>

    <HeaderJumbotron />
  </header>
</template>

<script>
import HeaderJumbotron from "@/components/HeaderJumbotron.vue";
export default {
  name: "HeaderPage",
  components: {
    HeaderJumbotron,
  },
};
</script>

<style lang="scss" scoped>
.header-top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #fff;
  color: white;
  padding: 20px 10%;
  box-shadow: 0 4px 2px -2px gray;
  z-index: 999;
  position: sticky;
  top: 0;
  left: 0;
}
.logo {
  cursor: pointer;
  width: 100px;
}
.links {
  list-style: none;
}
.links li {
  display: inline-block;
  padding: 0 10px;
}

.links a {
  text-decoration: none;
  color: gray;
  font-weight: bold;
  font-size: 15px;
}
</style>
