<template>
    <div>
        <router-view />
    </div>
</template>

<script>
// import Banner from './components/Banner.vue';
// import ContactUs from './components/ContactUs.vue';
// import Navbar from './components/Navbar.vue';
// import About from './components/About.vue';
// import Service from './components/Service.vue';
// import HowitWorks from './components/HowitWorks.vue';
// import CountriesPartners from './components/CountriesPartners.vue';
// import FAQ from "./components/FAQ.vue";
// import Footer from './components/Footer.vue';
// import Details from './components/Details.vue';
// import Home from './views/Home.vue';


export default {
  name: "App",
  components: {
    // Banner,
    // Navbar,
    // About,
    // Service,
    // CountriesPartners,
    // HowitWorks,
    // FAQ,
    // ContactUs,
    // Footer,
    // Details,
    // Home
  }
}
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

 @font-face {
    font-family: "DINNextLTArabic";
    src: url("./font/DINNextLTArabic-Regular-2.ttf") format('truetype');
  }

  div {
    /* position: relative; */
    font-family: 'DINNextLTArabic', sans-serif;
  }
</style>
