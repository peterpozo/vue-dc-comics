<template>
  <main>
    <div class="content"></div>
    <div class="blue-icons">
      <ul class="icons">
        <li>
          <a href="#!"
            ><img src="../img/buy-comics-digital-comics.png" alt="" />
            <span>DIGITAL COMICS</span></a
          >
        </li>
        <li>
          <a href="#!"
            ><img src="../img/buy-comics-merchandise.png" alt="" />
            <span>DIGITAL COMICS</span></a
          >
        </li>
        <li>
          <a href="#!"
            ><img src="../img/buy-comics-shop-locator.png" alt="" />
            <span>DIGITAL COMICS</span></a
          >
        </li>
        <li>
          <a href="#!"
            ><img src="../img/buy-comics-subscriptions.png" alt="" />
            <span>DIGITAL COMICS</span></a
          >
        </li>
        <!-- <li>
          <a href="#!"><img src="../img/buy-dc-power-visa.svg" alt="" /></a>
        </li> -->
      </ul>
    </div>
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
  text-decoration: none;
  color: white;
}

.icons a img {
  width: 40%;
}
</style>
