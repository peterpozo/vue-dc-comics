<template>
  <main>
    <div class="content"></div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.content {
  padding: 80px;
  background-color: #1c1c1c;
}

.blue-icons {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px 10%;
  background-color: #0282f9;
}

.icons {
  list-style: none;
}

.icons li {
  display: inline-block;
}

.icons a {
  display: flex;
  justify-content: center;
  align-items: center;
  text-decoration: none;
  color: white;
}

.icons a img {
  width: 30%;
}
</style>
