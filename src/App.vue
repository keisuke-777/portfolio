<template>
  <div id="app">
    <Header></Header>
    <br />
    <ScrollButton class="scroll"></ScrollButton>
    <About id="about"></About>
    <Product id="product"></Product>
    <Activity id="activity"></Activity>
    <Contact id="contact"></Contact>
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
  background-color: #f3f3ec;
}

.content-title {
  padding: 120px 0 20px 0;
  margin: 50px 20% 100px 20%;
  position: relative;
  font-size: 2em;
  color: #333;
  border-bottom: rgba(12, 50, 78, 0.4) 3px solid;
}
</style>
