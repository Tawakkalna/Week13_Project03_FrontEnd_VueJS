<template >
  <section lang="ar" dir="rtl">
    <div class="container">
      <nav class="navbar navbar-expand-lg mb-3">
        <ul class="navbar-nav justify-content-between align-items-center w-100">
          <li class="nav-item">
            <a href="#">
              <img src="../assets/logo.svg" alt="logo" />
            </a>
          </li>
          
          <div class="left-side">
                


            <svg class="svg-inline--fa fa-bell fa-w-14 fs-4" width="30" data-fa-transform="shrink-6" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="bell" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" data-fa-i2svg="" style="transform-origin: 0.4375em 0.5em;"><g transform="translate(224 256)"><g transform="translate(0, 0)  scale(0.625, 0.625)  rotate(0 0 0)"><path fill="currentColor" d="M224 512c35.32 0 63.97-28.65 63.97-64H160.03c0 35.35 28.65 64 63.97 64zm215.39-149.71c-19.32-20.76-55.47-51.99-55.47-154.29 0-77.7-54.48-139.9-127.94-155.16V32c0-17.67-14.32-32-31.98-32s-31.98 14.33-31.98 32v20.84C118.56 68.1 64.08 130.3 64.08 208c0 102.3-36.15 133.53-55.47 154.29-6 6.45-8.66 14.16-8.61 21.71.11 16.4 12.98 32 32.1 32h383.8c19.12 0 32-15.6 32.1-32 .05-7.55-2.61-15.27-8.61-21.71z" transform="translate(-224 -256)"></path></g></g></svg>

            <div class="dropdown1 text-end">
                <a href="#">عربي</a>

            <ul class="dropdown-content">
                <a href="#" class='dropdown-item'>عربي</a>
                <a href="#" class='dropdown-item'>English</a>
                <a href="#" class='dropdown-item'>Filipino</a>
                <a href="#" class='dropdown-item'>اردو</a>
                <a href="#" class='dropdown-item'>Indonesia</a>
            </ul>

            </div>
            <li class="nav-item d-inline-block">
                  <router-link class="nav-link" to="/">تسجيل الخروج</router-link>
                </li>
          </div>

          


          
        </ul>
      </nav>


      <div class="row justify-content-around main">
          <div class="col-2 vertical-navbar text-end">
              <ul class="nav-list">
                  <li class="mt-3">
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
                      <h3 class="fw-bold"> {{name}} </h3>
                  </div>

                  <div class="col-5">
                      <p>رقم الهوية الوطنية / هوية مقيم</p>
                      <h3 class="fw-bold"> {{id}} </h3>
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




          <div class="col-3 extra d-flex flex-column">
              <div class="row status text-end">
                  
                  <div class="row status-details">

                      <div class="loading text-center" v-if="loading">
                            <div class="spinner-border" role="status">
                              <span class="visually-hidden">Loading...</span>
                            </div>
                      </div>
                      <div class="col-10 align-self-center fs-5" v-else>
                      {{status}}
                      <br/>
                      آخر تحديث: {{currentTime}}
                      <br />
                      {{currentDay}}
                  </div>
                  <div class="col-2 d-flex flex-column justify-content-center align-items-center" v-if="!loading">

                      <a @click="updateStatus">
                          <svg class="svg-inline--fa fa-redo fa-w-16 mb-4" width="30" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="redo" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M500.33 0h-47.41a12 12 0 0 0-12 12.57l4 82.76A247.42 247.42 0 0 0 256 8C119.34 8 7.9 119.53 8 256.19 8.1 393.07 119.1 504 256 504a247.1 247.1 0 0 0 166.18-63.91 12 12 
                          0 0 0 .48-17.43l-34-34a12 12 0 0 0-16.38-.55A176 176 0 1 1 402.1 157.8l-101.53-4.87a12 12 0 0 0-12.57 12v47.41a12 12 0 0 0 12 12h200.33a12 12 0 0 0 12-12V12a12 12 0 0 0-12-12z"></path></svg>
                          </a>

                      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/QR_code_for_mobile_English_Wikipedia.svg/1200px-QR_code_for_mobile_English_Wikipedia.svg.png" alt="qrcode" width="45"/>

                  </div>
                  </div>

               
              </div>
                 <div class="extra-card health-status mt-4 py-3  h-100">
                      <div class="row justify-content-center align-items-center">
                          <div class="col-2">
                              <img src="../assets/left-arow.svg" alt="arrow" width="20"/>
                          </div>

                          <div class="col-8 text-end">
                              <h4 class="fw-bold fs-5">الوضع الصحي</h4>
                              <p>تفاصيل الوضع الصحي والألوان</p>

                          </div>

                          <div class="col-2">
                              <img src="../assets/left-arow.svg" alt="arrow" width="20"/>
                          </div>
                          
                      </div>
                  </div>

                  <div class="extra-card health-status mt-4 py-3 h-100">
                      <div class="row justify-content-center align-items-center">
                          <div class="col-2">
                              <img src="../assets/left-arow.svg" alt="arrow" width="20"/>
                          </div>

                          <div class="col-8 text-end">
                              <h4 class="fw-bold fs-5">استخدام كود QR زيارة مكان التجمع</h4>

                          </div>

                          <div class="col-2">
                              <img src="../assets/left-arow.svg" alt="arrow" width="20"/>
                          </div>
                          
                      </div>
                  </div>

                  <div class="extra-card health-status mt-4 py-3 h-100">
                      <div class="row justify-content-center align-items-center">
                          <div class="col-2">
                              <img src="../assets/left-arow.svg" alt="arrow" width="20"/>
                          </div>

                          <div class="col-8 text-end">
                              <h4 class="fw-bold fs-5">أفراد الأسرة والمكفولون</h4>

                          </div>

                          <div class="col-2">
                              <img src="../assets/left-arow.svg" alt="arrow" width="20"/>
                          </div>
                          
                      </div>
                  </div>

                   <div class="extra-card health-status mt-4 py-3 h-100">
                      <div class="row justify-content-center align-items-center">
                          <div class="col-2">
                              <img src="../assets/left-arow.svg" alt="arrow" width="20"/>
                          </div>

                          <div class="col-8 text-end">
                              <h4 class="fw-bold fs-5">إحصائيات وزارة الصحة COVID-19</h4>

                          </div>

                          <div class="col-2">
                              <img src="../assets/left-arow.svg" alt="arrow" width="20"/>
                          </div>
                          
                      </div>
                  </div>
              
          </div>
      </div>
    </div>
    <router-view/> 
  </section>
</template>




<script>
import $ from 'jquery'

let date = new Date();
let time = date.toTimeString().split(' ')[0]
let day = date.getFullYear()+'-'+(date.getMonth()+1)+'-'+date.getDate();

export default {
    data() {
        return {
            id: 1101234567,
            name: 'محمد راشد البلوي',
            isStatement : false,
            status: 'محصّن', 
            currentTime: time,
            currentDay: day,
            loading: false
        }
    },
    methods: {
        updateStatus(){
            let date = new Date();
            this.currentTime = date.toTimeString().split(' ')[0]
            this.currentDay = date.getFullYear()+'-'+(date.getMonth()+1)+'-'+date.getDate();
            this.loading = true
            setTimeout(()=> this.loading = false , 2000)
        }
    },
    mounted() {
        $('body').css('background-color', '#f9f9f9');
        $('#app').css('margin', 'auto');
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
    /* background-color: greenyellow; */
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
    padding: 5px;
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

.status{
    border-radius: 11px;
    color: white;
    padding: 20px;
    background: linear-gradient(261deg, rgba(34,116,47,1) 0%, rgba(0,60,35,1) 100%);
}

.status img{
    filter: invert(100%);
}

.left-side{
    width: 30%;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
}

.left-side a{
    color: #636363;
    text-decoration: none;
}

.dropdown1{
    position: relative;
}

.dropdown-content{
    display: none;
    position: absolute;
    background-color: white;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
    margin-top: 0px;
    padding: 10px 12px 10px 35px;
}
.dropdown-content a{
    display: block;
}
.dropdown1:hover .dropdown-content{
    display: block;
}

.dropdown1:hover a{
    display: block;
}

.dropdown-item{
    margin: 10px 0px ;
}

.health-status{
    background-color: white;
    border-radius: 5px;
    box-shadow: 0px 5px 15px rgba(0,0,0,0.3);
}

.extra-card{
    cursor: pointer;
    transition: background-color 0.2s;
}

.extra-card:hover{
    background-color: #e8eff7;
}
</style>