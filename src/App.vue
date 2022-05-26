<template>
  <div id="app">
    <Header />
    <Section />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Contact from "./components/Contact.vue";
import Header from "./components/Header.vue";
import Section from "./components/Section.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Section,
    Contact,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: "Lato", sans-serif;
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  overflow-x: hidden;
  background-color: #f7f7f7;
  position: relative;
}
</style>
