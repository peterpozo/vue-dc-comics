<template>
  <footer>
    <section class="shop">
      <div class="container">
        <div class="block">
          <img src="@/img/buy-comics-digital-comics.png" alt="digital comics" />
          <span><a href="">DIGITAL COMICS</a></span>
        </div>
        <div class="block">
          <img src="@/img/buy-comics-merchandise.png" alt="merchandise" />
          <span><a href=""> DC MERCHANDISE</a></span>
        </div>
        <div class="block">
          <img src="@/img/buy-comics-subscriptions.png" alt="subscriptionS" />
          <span><a href="">SUBSCRIPTION</a></span>
        </div>
        <div class="block">
          <img src="@/img/buy-comics-shop-locator.png" alt="shop locator" />
          <span><a href="">COMIC SHOP LOCATOR</a></span>
        </div>
        <div class="block">
          <img src="@/img/buy-dc-power-visa.svg" alt="power visa" />
          <span><a href="">DC POWER VISA</a></span>
        </div>
      </div>
    </section>
    <section class="background">
      <div class="blocks">
        <div class="left-block">
          <ul>
            <h2>DC COMICS</h2>
            <li><a href="">Characters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">News</a></li>
          </ul>
          <ul>
            <h2>SHOP</h2>
            <li><a href="">Shop DC</a></li>
            <li><a href="">Shop DC collectibles</a></li>
          </ul>
        </div>
        <div class="center-block">
          <ul>
            <h2>DC</h2>
            <li><a href="">Terms of use</a></li>
            <li><a href="">Privacy Policy (New)</a></li>
            <li><a href="">Ad Choices</a></li>
            <li><a href="">Advertising</a></li>
            <li><a href="">Jobs</a></li>
            <li><a href="">Subscriptions</a></li>
            <li><a href="">Talent Workshops</a></li>
            <li><a href="">CPSC Certificates</a></li>
            <li><a href="">Ratings</a></li>
            <li><a href="">Shop Help</a></li>
            <li><a href="">Contact Us</a></li>
          </ul>
        </div>
        <div class="right-block">
          <ul>
            <h2>SITES</h2>
            <li><a href="">DC</a></li>
            <li><a href="">MAD Magazine</a></li>
            <li><a href="">DC Kids</a></li>
            <li><a href="">DC Universe</a></li>
            <li><a href="">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <img src="@/img/dc-logo-bg.png" alt="" />
    </section>
    <section class="sub-footer">
      <div class="container">
        <button>SIGN-UP NOW!</button>
        <div class="block-left">
          <span>FOLLOW US</span>
          <a href="">
            <img src="@/img/footer-facebook.png" alt="facebook" />
          </a>
          <a href="">
            <img src="@/img/footer-twitter.png" alt="twitter" />
          </a>
          <a href=""><img src="@/img/footer-youtube.png" alt="youtube" /> </a>
          <a href="">
            <img src="@/img/footer-pinterest.png" alt="pinterest" />
          </a>
          <a href=""
            ><img src="@/img/footer-periscope.png" alt="periscope" />
          </a>
        </div>
      </div>
    </section>
  </footer>
</template>

<script>
export default {
  name: "FooterPage",
};
</script>

<style lang="scss" scoped>
.shop {
  background-color: #0282f9;
  padding: 2.5rem;
  .container {
    max-width: 1200px;
    margin: auto;
    display: flex;
    gap: 2.5rem;
    justify-content: center;
    align-items: center;
    font-size: 0.7rem;
    .block {
      flex: 0 1 20%;
      display: flex;
      gap: 1rem;
      justify-content: flex-start;
      align-items: center;
      img {
        width: 20%;
      }
      span {
        width: 80%;
        font-size: 0.8rem;
        color: white;
        a {
          text-decoration: none;
          &:visited,
          &:hover,
          &:active {
            color: inherit;
          }
        }
      }
    }
  }
}
.background {
  position: relative;
  overflow: hidden;
  gap: 10rem;
  background-image: url("@/img/footer-bg.jpg");
  background-size: cover;
  padding: 2.5rem 0 4.5rem 4.5rem;
  .blocks {
    display: flex;
    gap: 5rem;
    font-size: 0.7rem;
    color: white;
    margin-left: 4rem;
    .left-block {
      display: flex;
      flex-direction: column;
      gap: 2rem;
    }
    ul {
      list-style: none;
      h2 {
        margin-bottom: 1rem;
      }
      li {
        color: #7f807b;
        margin-bottom: 0.5rem;
        a {
          text-decoration: none;
          &:visited,
          &:hover,
          &:active {
            color: inherit;
          }
        }
      }
    }
  }
  img {
    width: 40%;
    position: absolute;
    top: -6.5rem;
    left: 50rem;
  }
}
.sub-footer {
  height: 5rem;
  background-color: #303030;
  .container {
    max-width: 1200px;
    margin: auto;
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    button {
      height: fit-content;
      padding: 0.6rem 0.8rem;
      background-color: transparent;
      border: 2px solid #0282f9;
      color: white;
      font-size: 1rem;
      font-weight: bold;
    }
    .block-left {
      display: flex;
      gap: 1rem;
      align-items: center;
      a {
        width: 9%;
        img {
          width: 100%;
        }
      }
      span {
        color: #0282f9;
        font-weight: bold;
        font-size: 1.2rem;
        margin-right: 0.5rem;
      }
    }
  }
}
</style>
