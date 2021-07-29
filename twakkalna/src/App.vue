<template>
  <div class="container" lang="ar" dir="rtl">
    <HowitWorks />
  </div>
</template>

<script>
import HowitWorks from './components/HowitWorks.vue'

export default {
  name: 'App',
  components: {
    HowitWorks
  }
}
</script>

<style>

 @font-face {
    font-family: "DINNextLTArabic";
    src: url("./font/DINNextLTArabic-Regular-2.ttf") format('truetype');
}

div {
  /* position: relative; */
  font-family: 'DINNextLTArabic', sans-serif;
}

</style>
