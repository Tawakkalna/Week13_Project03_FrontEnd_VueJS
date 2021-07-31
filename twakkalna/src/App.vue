<template>
  <FAQ />
</template>

<script>
import FAQ from "./components/FAQ.vue";

export default {
  name: "App",
  components: {
    FAQ,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

@import "~bootstrap/dist/css/bootstrap.css";
</style>
