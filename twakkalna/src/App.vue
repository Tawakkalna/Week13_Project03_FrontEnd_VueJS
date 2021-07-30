<template>
    <div class="container">
        <ContactUs/>
    </div>
</template>

<script>
import ContactUs from './components/ContactUs.vue';

export default {
  name: "App",
  components: {
    ContactUs,
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
