<template>
  <div id="app">
    <Header></Header>
    <ScrollButton class="scroll"></ScrollButton>
    <Content title="About"></Content>
    <Content title="Product"></Content>
    <Content title="Activity"></Content>
    <Content title="Contact"></Content>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import ScrollButton from "./components/ScrollButton.vue";
import Content from "./components/Content.vue";
import Footer from "./components/Footer.vue";
import "normalize.css";

export default {
  name: "App",
  components: {
    Header,
    ScrollButton,
    Content,
    Footer,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@200&display=swap");
#app {
  font-family: "Raleway", sans-serif;
  text-align: center;
}
</style>
