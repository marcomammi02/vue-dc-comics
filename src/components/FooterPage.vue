<template>
  <div class="footer">
    <div class="list-area">
      <div class="container-list-area">
        <div class="dc-comics-and-shop-list">
          <ul class="footer-list">
            <h2>DC COMICS</h2>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <ul class="footer-list second">
            <h2>SHOP</h2>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
        <ul class="footer-list">
          <h2>DC</h2>
          <li>Terms Of Use</li>
          <li>Privacu Policy (New)</li>
          <li>Add Choices</li>
          <li>Advertisings</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
        <ul class="footer-list">
          <h2>SITES</h2>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
        <img src="@/img/dc-logo-bg.png" alt="">
      </div>
    </div>
    <div class="footer-space"></div>
    <div class="link-area">
      <div class="container-link-area">
        <div class="btn">SIGN-UP NOW!</div>
        <ul>
          <li class="footer-link-text">FOLLOW US</li>
          <li><img src="@/img/footer-facebook.png" alt=""></li>
          <li><img src="@/img/footer-twitter.png" alt=""></li>
          <li><img src="@/img/footer-youtube.png" alt=""></li>
          <li><img src="@/img/footer-pinterest.png" alt=""></li>
          <li><img src="@/img/footer-periscope.png" alt=""></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style>

.list-area {
  background-image: url("@/img/footer-bg.jpg");
  position: absolute;
  left: 0;
  right: 0;
  z-index: -2;
}

.container-list-area {
  max-width: 1100px;
  margin: 0 auto;
  display: flex;
  padding: 2rem 0 3rem;
  position: relative;
  height: 305px;
}

.footer-list {
  display: block;
  margin-right: 30px;
  color: #a6a6a6;
}

.footer-list.second{
  margin-top: 10px;
}

.footer-list h2 {
  font-size: 1.4rem;
  margin: 1rem 0;
  color: #ffffff;
}

.list-area img {
  width: 40%;
  position: absolute;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
  z-index: -1;
}

.footer-space {
  height: 305px;
}

.link-area {
  background-color: #303030;
  height: 90px;
  position: absolute;
  left: 0;
  right: 0;
}

.container-link-area {
  max-width: 1100px;
  margin: 20px auto 0;
  display: flex;
  justify-content: space-between;
}

.btn {
  font-size: 1.3rem;
  color: #ffffff;
  border: 3px solid #0282f9;
  width: fit-content;
  padding: 10px;
}

.btn:hover {
  background-color: #0282f9;
  border-radius: 8px;
  transition: .5s ease-in-out;
}

.footer-link-text {
  font-size: 1.5rem;
  color: #0282f9;
}

.link-area img {
  width: 30px;
  margin-left: 20px;
}
</style>
