<template>
    <div class="container">
        <Navbar/>
        <Banner/>
        <div class="margin-top-100px" dir="rtl" lang="ar">
          <About/>
        </div>
    </div>
</template>

<script>
import Banner from './components/Banner.vue';
import Navbar from './components/Navbar.vue';
import About from './components/About.vue';

export default {
  name: "App",
  components: {
    Banner,
    Navbar,
    About
  }
}
</script>

<style>
  .margin-top-100px {
    margin-top: 230px;
  }

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
