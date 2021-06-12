<template>
  <div>
    <button class="sc-button" v-on:click="smoothScrollFunc('#about')">
      About
    </button>
    <!-- 自己紹介的なことを書く -->
    <button class="sc-button" v-on:click="smoothScrollFunc('#product')">
      Product
    </button>
    <!-- いわゆる製作物を書く -->
    <button class="sc-button" v-on:click="smoothScrollFunc('#activity')">
      Activity
    </button>
    <!-- 課外活動とか表彰経験書く？？ -->
    <button class="sc-button" v-on:click="smoothScrollFunc('#contact')">
      Contact
    </button>
    <!-- アカウントリスト -->
  </div>
</template>

<script>
export default {
  components: {},
  methods: {
    smoothScrollFunc(target) {
      event.preventDefault();
      this.$SmoothScroll(document.querySelector(target), 800, null, null, "y");
    },
  },
};
</script>

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