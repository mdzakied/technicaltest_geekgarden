<template>
  <div id="app" class="h-100">
    <Hero />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";
import Main from "./views/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    Hero,
    Main,
    Footer,
  },
};
</script>