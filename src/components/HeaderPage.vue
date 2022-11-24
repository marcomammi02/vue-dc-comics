<template>
  <div class="header">
    <img src="@/img/dc-logo.png" alt="">
    <ul class="header-menu">
      <li>CHARACTER</li>
      <li>COMICS</li>
      <li>MOVIES</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>COLLECTIBLES</li>
      <li>VIDEOS</li>
      <li>FANS</li>
      <li>NEWS</li>
      <li>SHOP</li>
    </ul>
  </div>
</template>

<script>
export default {

};
</script>

<style>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1100px;
  margin: 0 auto;
}

.header img {
  width: 70px;
}

.header-menu {
  display: flex;
  list-style-type: none;
}

.header-menu li {
  margin: 0 10px;
  font-weight: 600;
  padding: 35px 0;
}

.header-menu li:hover {
  color: #0282f9;
  padding: 35px 0 30px;
  border-bottom: 5px solid #0282f9;
}
</style>
