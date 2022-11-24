<template>
  <div class="main">
    <div class="content-area">
      <h1>Content goes here</h1>
    </div>
    <div class="menu-area">
      <ul>
        <li>
          <img src="@/img/buy-comics-digital-comics.png" alt="">
          <p>DIGITAL COMICS</p>
        </li>
        <li>
          <img src="@/img/buy-comics-merchandise.png" alt="">
          <p>DC MERCHANDISE</p>
        </li>
        <li>
          <img src="@/img/buy-comics-subscriptions.png" alt="">
          <p>SUBSCRIPTION</p>
        </li>
        <li>
          <img src="@/img/buy-comics-shop-locator.png" alt="">
          <p>COMIC STORE LOCATOR</p>
        </li>
        <li>
          <img src="@/img/buy-dc-power-visa.svg" alt="">
          <p>DC POWER VISA</p>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style>
.main {
  background-color: #0282f9;
}

.content-area {
  background-color: #000000;
  padding: 3rem 0;
}

.content-area h1 {
  color: #ffffff;
  font-size: 1.5rem;
  margin-left: 15rem;
}

.menu-area {
  max-width: 1100px;
  padding: 3rem 0;
  margin: 0 auto;
}

ul {
  display: flex;
  justify-content: space-evenly;
}

li {
  display: flex;
  align-items: center;
}

img {
  width: 40px;
}

li:nth-child(4) img{
  width: 30px;
}

p {
  color: #ffffff;
  margin-left: 10px;
}
</style>
