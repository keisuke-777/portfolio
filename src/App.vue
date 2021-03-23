<template>
  <div id="app">
    <Header></Header>
    <ScrollButton class="scroll"></ScrollButton>
    <About></About>
    <Product></Product>
    <Activity></Activity>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import ScrollButton from "./components/ScrollButton.vue";
import About from "./components/About.vue";
import Product from "./components/Product.vue";
import Activity from "./components/Activity.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
import "normalize.css";

export default {
  name: "App",
  components: {
    Header,
    ScrollButton,
    About,
    Product,
    Activity,
    Contact,
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
