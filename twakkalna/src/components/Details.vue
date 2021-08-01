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




          <div class="col-6 information">
              <div class="row person-info mb-4 px-5 py-3 text-end">

                  <div class="col-7">
                      <p>الاسم</p>
                      <h3 class="fw-bold">محمد راشد البلوي</h3>
                  </div>

                  <div class="col-5">
                      <p>رقم الهوية الوطنية / هوية مقيم</p>
                      <h3 class="fw-bold">1101234567</h3>
                  </div>
              </div>

              <div class="row  h-75">
                  <div class="statements col text-end">
                      <div class="p-3">
                          <svg class="svg-inline--fa fa-check-circle fa-w-16 text-primary ms-1" width="15" aria-hidden="true" focusable="false" data-prefix="far" data-icon="check-circle" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M256 8C119.033 8 8 119.033 8 256s111.033 248 248 248 248-111.033 248-248S392.967 8 256 8zm0 48c110.532 0 200 89.451 200 200 0 110.532-89.451 200-200 200-110.532 0-200-89.451-200-200 0-110.532 89.451-200 200-200m140.204 130.267l-22.536-22.718c-4.667-4.705-12.265-4.736-16.97-.068L215.346 303.697l-59.792-60.277c-4.667-4.705-12.265-4.736-16.97-.069l-22.719 22.536c-4.705 4.667-4.736 12.265-.068 16.971l90.781 91.516c4.667 4.705 12.265 4.736 16.97.068l172.589-171.204c4.704-4.668 4.734-12.266.067-16.971z"></path></svg>

                      <span>التصاريح القائمة</span>
                      </div>

                      <div v-if="!isStatement" class="d-flex flex-column justify-content-center align-items-center h-75">
                          <svg class="svg-inline--fa fa-calendar-times fa-w-14 fs-3 text-secondary" width="45" aria-hidden="true" focusable="false" data-prefix="far" data-icon="calendar-times" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" data-fa-i2svg=""><path fill="currentColor" d="M311.7 374.7l-17 17c-4.7 4.7-12.3 4.7-17 0L224 337.9l-53.7 53.7c-4.7 4.7-12.3 4.7-17 0l-17-17c-4.7-4.7-4.7-12.3 0-17l53.7-53.7-53.7-53.7c-4.7-4.7-4.7-12.3 0-17l17-17c4.7-4.7 12.3-4.7 17 0l53.7 53.7 53.7-53.7c4.7-4.7 12.3-4.7 17 0l17 17c4.7 4.7 4.7 12.3 0 17L257.9 304l53.7 53.7c4.8 4.7 4.8 12.3.1 17zM448 112v352c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V112c0-26.5 21.5-48 48-48h48V12c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v52h128V12c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v52h48c26.5 0 48 21.5 48 48zm-48 346V160H48v298c0 3.3 2.7 6 6 6h340c3.3 0 6-2.7 6-6z"></path></svg>
                          <br/>
                          لا توجد تصاريح
                      </div>
                  
              </div>
              </div>
          </div>




          <div class="col-3 extra">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aspernatur magnam, vitae alias temporibus sequi impedit hic accusantium. Quasi vel aliquid perferendis tempore voluptatum. Aut, sed corporis officia commodi minima perspiciatis amet explicabo praesentium, est voluptatum aperiam excepturi consequatur numquam! Soluta dolor, sed officiis officia voluptatibus nesciunt fugiat nemo quam voluptas!
          </div>
      </div>
    </div>
  </section>
</template>




<script>
import $ from 'jquery'
export default {
    data() {
        return {
            isStatement : false
        }
    },

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
    cursor: pointer;
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

.person-info , .statements{
    background-color: white;
    border-radius: 5px;
    box-shadow: 0px 5px 15px rgba(0,0,0,0.3);
}
.person-info p{
    color: grey;
    font-size: 14px;
}

</style>