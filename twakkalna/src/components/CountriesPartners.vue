<template>
  <main>
                  <section class="register" id="countries">
                <div class="container countriesShape">
                    <h2 class="title mr-md-4" data-aos="fade-down" data-aos-duration="200">
                        دول المرحلة الأولى التي يعمل فيها تطبيق توكلنا
                    </h2>
                    <div class="row">
                        <div class="col-md-12">
                            <div class=" d-flex flex-wrap">
                                <div class="countryCard">
                                    <div class="countryFlag" id="SaudiArabia" ></div>
                                    <p class="mt-2">المملكة العربية السعودية</p>
                                </div>
                                <div class="countryCard">
                                    <div class="countryFlag" id="uae" ></div>
                                    <p class="mt-2">الإمارات العربية المتحدة</p>
                                </div>
                                <div class="countryCard">
                                    <div class="countryFlag" id="Bahrain" ></div>
                                    <p class="mt-2">البحرين</p>
                                </div>
                                <div class="countryCard">
                                    <div class="countryFlag" id="Kuwait" ></div>
                                    <p class="mt-2">الكويت</p>
                                </div>
                                
                                <div class="countryCard">
                                    <div class="countryFlag" id="qatar" ></div>
                                    <p class="mt-2">دولة قطر</p>
                                </div>
                                <div class="countryCard">
                                    <div class="countryFlag" id="Oman" ></div>
                                    <p class="mt-2">سلطنة عمان</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-12" style="direction: rtl;">
                                <a href="countries.html" class="btn seeMoreBtn rounded-pill mx-md-3 my-4"> 
                                    <span>عرض المزيد</span>
                                    <i class="fas fa-chevron-left mr-2"></i>
                                    </a>
                        </div>
                        </div>
                </div>
                    
            </section>

            <section class="partners">
                <h2 class="title" data-aos="zoom-in" data-aos-duration="200">
                    شركاء النجاح
                </h2>
                <div class="row countries">
                    <div class="col-4">
                        <h5 data-aos="zoom-in" data-aos-duration="200" class="title stcMB">الشريك الإستراتيجي</h5>
                        <div class="stc">
                            <a href="javascript:;" class="not-active" data-aos="zoom-in" data-aos-duration="400"><img
                                    src="../images/stc.png" alt="" /></a>
                        </div>
                    </div>

                    <div class="col-4">
                        <h5 class="title text-center" data-aos="zoom-in" data-aos-duration="200">
                            الشركاء التقنيين
                        </h5>
                        <br />
                        <ul>
                            <li>
                                <a href="javascript:;" class="not-active" data-aos="zoom-in"
                                    data-aos-duration="400"><img src="../images/p1.png" alt="" /></a>
                            </li>
                            <li>
                                <a href="javascript:;" class="not-active" data-aos="zoom-in"
                                    data-aos-duration="400"><img src="../images/p6.png" alt="" /></a>
                            </li>

                        </ul>
                    </div>
                    <div class="col-4">

                        <h2 class="title" data-aos="zoom-in" data-aos-duration="200">
                            شكراً لكم
                        </h2>
                        <ul>
                            <li>
                                <a href="javascript:;" class="not-active" data-aos="zoom-in"
                                    data-aos-duration="400"><img width="100" height="100" src="../images/p5.png" alt="" /></a>
                            </li>
                        </ul>
                        <br />
                    </div>
                </div>
            </section>
   </main>
</template>

<script>
export default {

}
</script>

<style scoped>
.stc {
    display: -webkit-box;
    display: -moz-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -moz-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    position: relative;
}
.stc:before {
    content: "";
    background: #ffffff;
    position: absolute;
    width: 100%;
    padding: 70px 60px;
    top: 40px;
    border-top-right-radius: 14px;
    border-bottom-right-radius: 14px;
}

.stc img {
    position: relative;
    z-index: 2;
    margin: 80px 60px;
}
.register{
    direction: rtl;
}
#SaudiArabia{
    background-image: url(../images/SaudiArabia.png);
}
#uae{
    background-image: url(../images/uae.png);
}
#Bahrain{
    background-image: url(../images/Bahrain.svg);
}
#Kuwait{
    background-image: url(../images/Kuwait.png);
}
#qatar{
    background-image: url(../images/qatar.png);
}
#Oman{
    background-image: url(../images/Oman.png);
}
.partners{
    background-color: #1FA99A;
    color: white;
}
li{
    list-style: none;
    float: left;
    margin-right: 50px;
}

.flagsContainer {
    height: 430px;
}
.countryCard {
    width: 130px;
    max-width: 130px;
    text-align: center;
    margin: 10px;
}
.countryFlag {
    display: block;
    width: 55px;
    height: 55px;
    border-radius: 50%;
    background-size: cover;
    background-position-x: center;
    margin: 0 auto;
    border: 1px solid #f4f4f4;
}
.seeMoreBtn {
    /* background-color: #1FA99A; */
    background: rgb(8,100,79);
    background: linear-gradient(47deg, rgba(8,100,79,1) 0%, rgba(20,159,144,1) 100%);
    color: white;
    padding: 8px 30px;
    transition: all 0.2 ease-in-out;
}
.seeMoreBtn:hover {
    color: white;
    opacity: 0.9;
    transition: all 0.2 ease-in-out;

}
#countries {
    position: relative;
}
#countries::after {
    content: "";
    background: url(../images/globe.svg) no-repeat left bottom;
    width: 100%;
    height: 100%;
    position: absolute;
    z-index: -2;
    right: 0;
    bottom: -146px;
    opacity: 0.1;
    background-size: 42%;
    background-position-y: top;

    
}
@media only screen and (max-width: 544px) {
    #countries::after {
       
        bottom: 58px;
        background-position-x: right
    
        
    }
}
  .textJustify{
    text-align: justify;
}
.stcMB{
    margin-bottom: 8px;
}
.countries{
    margin-right: 0px;
}
</style>