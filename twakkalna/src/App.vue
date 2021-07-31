<template>
    <div class="container">
        <Navbar/>
        <Banner/>
        <div class="margin-top-100px" dir="rtl" lang="ar">
          <About/>
          <Service />
          <HowitWorks />
        </div>
        <CountriesPartners />
    </div>
</template>

<script>
import Banner from './components/Banner.vue';
import Navbar from './components/Navbar.vue';
import About from './components/About.vue';
import Service from './components/Service.vue';
import HowitWorks from './components/HowitWorks.vue';
import CountriesPartners from './components/CountriesPartners.vue';

export default {
  name: "App",
  components: {
    Banner,
    Navbar,
    About,
    Service,
    CountriesPartners,
    HowitWorks
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

 @font-face {
    font-family: "DINNextLTArabic";
    src: url("./font/DINNextLTArabic-Regular-2.ttf") format('truetype');
  }

  div {
    /* position: relative; */
    font-family: 'DINNextLTArabic', sans-serif;
  }
</style>
