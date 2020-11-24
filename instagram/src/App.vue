<template>
  <div id="app">
    <Content />
    <Footer />
  </div>
</template>

<script>
import Content from "./components/template/Content";
import Footer from "./components/template/Footer";
import "./main";

export default {
  name: "App",
  components: { Content, Footer },
};
</script>

<style>
#app {
  display: grid;
  grid-template-areas:
    "content-wrapper content-wrapper"
    "footer footer";
}
</style>
