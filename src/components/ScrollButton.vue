<template>
  <div>
    <button class="sc-button">About</button>
    <!-- 自己紹介的なことを書く -->
    <button class="sc-button">Product</button>
    <!-- いわゆる製作物を書く -->
    <button class="sc-button">Activity</button>
    <!-- 課外活動とか表彰経験書く？？ -->
    <button class="sc-button">Contact</button>
    <!-- アカウントリスト -->
  </div>
</template>

<style>
.sc-button {
  padding: 80px;
  border: none;
  border-radius: 5px;
  margin: 10px;
  outline: none;
}
.sc-button:hover {
  cursor: pointer;
  text-decoration: none;
  -webkit-animation: sc-button 0.5s both;
  -moz-animation: sc-button 0.5s both;
  animation: sc-button 0.5s both;
}
@-webkit-keyframes sc-button {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
  }
  100% {
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
  }
}
@-moz-keyframes sc-button {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
  }
  100% {
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
  }
}
@keyframes sc-button {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
  }
  100% {
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
  }
}
</style>