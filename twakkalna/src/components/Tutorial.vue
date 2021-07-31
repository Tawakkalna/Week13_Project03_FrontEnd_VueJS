<template>
  <div class="row m-5">
      <div class="col-6">
          <div class="tab-content-area">
              <div class="tab-content active"> <iframe width="550" height="333" src="https://www.youtube.com/embed/FN9JCUfLzzA"/> </div>
              <div class="tab-content"> <iframe width="550" height="333" src="https://www.youtube.com/embed/69oJQMRhips"/> </div>
              <div class="tab-content"> <iframe width="550" height="333" src="https://www.youtube.com/embed/fW4c7ma1tUY"/> </div>
              <div class="tab-content"> <iframe width="550" height="333" src="https://www.youtube.com/embed/YF0bz_TrCDM"/> </div>
          </div>
      </div>
      <div class="col-6">
          <h1 class="fw-bold mb-5">كيف يعمل توكلنا؟</h1>

          <ul class="tabs">
              <li class="tab active-tab"> كيف تسجل في توكلنا </li>
              <li class="tab"> للأفراد </li>
              <li class="tab"> أثناء فترة المنع الجزئي </li>
              <li class="tab"> تصاريح تطبيقات التوصيل السريع </li>
          </ul>
          
      </div>
      

      
  </div>
</template>

<script>
import $ from 'jquery';

export default {
    name: 'Tutorial',
    mathods: {
        //
    },
    mounted() {
        $('.tabs li').click(function () { 
            let index = $(this).index();
            $('.tab').removeClass('active-tab');
            $(this).addClass('active-tab');
            $('.tab-content').hide(100);
            $('.tab-content').eq(index).show(100);
        });
    },

}
</script>

<style scoped>
h1{
    color: #333e4b;
}
li{
    list-style-type: none;
}
iframe{
    border-radius: 15px;
}
.tabs{
    padding: 0px;
}
.tab-content{
    display: none;
}
.active{
    display: block;
}
.active-tab{
    background-color: #f0f3fa;
    font-weight: bold;
}
.tab{
    border-radius: 15px;
    padding: 15px 30px;
    margin: 10px 0px;
    cursor: pointer;
    transition: 0.5s;
}
.tab:hover{
    background-color: #f0f3fa;
    font-weight: bold;
}
</style>