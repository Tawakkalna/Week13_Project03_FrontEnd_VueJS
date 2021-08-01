<template >
  <section lang="ar" dir="rtl">
    <div class="container">
      <nav class="navbar navbar-expand-lg">
        <ul class="navbar-nav justify-content-between align-items-center w-100">
          <li class="nav-item">
            <a href="#">
              <img src="../assets/logo.svg" alt="logo" />
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">تسجيل الخروج</a>
          </li>
        </ul>
      </nav>


      <div class="row justify-content-around main">
          <div class="col-2 vertical-navbar text-end">
              <ul class="nav-list">
                  <li class="my-5">
                      <a href="#">
                      <span> <img src="../assets/arrow-left.png" alt="icon" width="20"/> </span> 
                      الرئيسية     
                      </a>
                      
                  </li>

                  <li class="my-5">
                      <a href="#">
                      <span> <img src="../assets/arrow-left.png" alt="icon" width="25"/> </span> 
                      التصاريح 
                      </a>
                  </li>

                  <li class="my-5">
                      <a href="#">
                      <span> <img src="../assets/arrow-left.png" alt="icon" width="25"/> </span> 
                      البلاغات 
                      </a>
                  </li>

                  <li class="my-5">
                      <a href="#">
                      <span> <img src="../assets/arrow-left.png" alt="icon" width="25"/> </span> 
                      التنبيهات 
                      </a>
                  </li>

                  <li class="my-5">
                      <a href="#">
                      <span> <img src="../assets/arrow-left.png" alt="icon" width="25"/> </span> 
                      لوحة البيانات 
                      </a>
                  </li>

                  <li class="my-5">
                      <a href="#">
                      <span> <img src="../assets/arrow-left.png" alt="icon" width="25"/> </span> 
                      التبرع بالأعضاء 
                      </a>
                  </li>


                  <li class="my-5">
                      <a href="#">
                      <span> <img src="../assets/arrow-left.png" alt="icon" width="25"/> </span> 
                      الجواز الصحي 
                      </a>
                  </li>
              </ul>
          </div>



      </div>
    </div>
  </section>
</template>




<script>
import $ from 'jquery'
export default {

    mounted() {
        $('body').css('background-color', '#f9f9f9');
    },
    
}
</script>
<style scoped>

li{
    list-style: none;
}

.nav-link{
    color: #636363;
}
.main{
    /*  */
}

.vertical-navbar{
    background: rgb(34,193,195);
    background: linear-gradient(0deg, rgba(34,193,195,1) 0%, rgba(194,174,131,1) 100%);

    border-radius: 7px;
}
.information{
    background-color: aqua;
}

.extra{
    background-color: greenyellow;
}
.nav-list a{
    color: white;
    text-decoration: none;
}

.nav-list{
    padding: 0;
    
}

.nav-list li{
    transition: transform 1s;
    border-radius: 4px;
}
.nav-list li:hover{
    background-color: white;
    transform: scale(1.1); 
    box-shadow: 0 4px 8px 0;
}

.nav-list li:hover a{
    color: black;
}
.nav-list li:hover img{
    filter: invert(100%);
}


</style>