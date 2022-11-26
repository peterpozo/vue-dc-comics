<template>
  <div class="card">
    <img
      src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
      alt=""
    />
    <h5>Action Comics</h5>
  </div>
</template>

<script>
export default {
  name: "CardComics",
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
