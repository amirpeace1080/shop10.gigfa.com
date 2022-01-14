<template>
  <div>
    <Navbar />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style>
@import url("./assets/css/reset.css");
@import url("./assets/css/header.css");
@import url("./assets/css/main.css");
@import url("./assets/css/footer.css");
@import url("./assets/css/media.css");

html,
body {
  font-family: Vazir, sans-serif;
}
</style>
