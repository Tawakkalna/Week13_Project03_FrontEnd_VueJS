<template>
  <div class="home">
    <Navbar/>
        <Banner/>
        <div class="margin-top-100px" dir="rtl" lang="ar">
          <About/>
          <Service />
          <HowitWorks />
        </div>
        <FAQ />
        <CountriesPartners />
        <ContactUs />
        <Footer />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue';
import ContactUs from '../components/ContactUs.vue';
import Navbar from '../components/Navbar.vue';
import About from '../components/About.vue';
import Service from '../components/Service.vue';
import HowitWorks from '../components/HowitWorks.vue';
import CountriesPartners from '../components/CountriesPartners.vue';
import FAQ from "../components/FAQ.vue";
import Footer from '../components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Banner,
    Navbar,
    About,
    Service,
    CountriesPartners,
    HowitWorks,
    FAQ,
    ContactUs,
    Footer,
  }
}
</script>


<style scoped>
  .margin-top-100px {
    margin-top: 230px;
  }
</style>