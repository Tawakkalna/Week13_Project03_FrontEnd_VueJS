<template>
  <Service />
  <CountriesPartners />

</template>

<script>
import Service from './components/Service.vue'
import CountriesPartners from './components/CountriesPartners.vue'

export default {
  name: 'App',
  components: {
    Service,
    CountriesPartners
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
</style>
