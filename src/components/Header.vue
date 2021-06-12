<template>
  <div class="header">
    <div class="header-inner">
      <h1 class="title" @click="smoothScrollFunc('#app')">kei-777.com</h1>
    </div>
  </div>
</template>

<script>
// import ScrollButton from "./ScrollButton.vue";
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
.header {
  background-color: #03111a;
  position: sticky;
  top: 0;
  width: 100%;
  z-index: 1;
}
.header-inner {
  margin-left: 5%;
  margin-right: 5%;
  display: flex;
}
.title {
  padding: 20px 0px;
  margin: unset;
  cursor: pointer;
}
.nav {
  margin: auto;
  margin-right: 0;
  padding: auto;
}
</style>