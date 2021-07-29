<template>
    <div class="container">
        <Banner/>
    </div>
</template>

<script>
import Banner from "./components/Banner.vue";

export default {
  name: "App",
  components: {
    Banner,
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
