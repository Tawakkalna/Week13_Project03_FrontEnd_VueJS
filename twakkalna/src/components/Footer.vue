<template>
  <footer>
            <div class="container">
                <div class="footer-content">

                    <div class="row">
                        <div class="col-lg-4 col-12 foot4">
                            <div class="download-apps">
                                <label>تحميل التطبيق</label>
                                <img src='../assets/huaweigalary.png' alt='store' />
                                <img src='../assets/appstore.png' alt='store' />
                                <img src='../assets/googleplay.png' alt='store' />
                            </div>
                        </div>

                        <div class="col-lg-5 col-12 foot2">
                            <div class="footer-block">
                                <ul>
                                    <li><a href="TawakkalnaAr.pdf" target="_blank">دليل الإستخدام</a></li>
                                    <!-- <li><a href="gatheringManagementServiceAR.pdf"  target="_blank">خدمة إدارة التجمعات</a></li> -->
                                    <!-- <li><a href="signUp.pdf"  target="_blank">طريقة التسجيل في تطبيق توكلنا </a></li> -->
                                    <li><a href="privacy.html">سياسة الخصوصية</a></li>
                                    <li><a href="terms.html">الشروط والأحكام</a></li>
                                    
                                </ul>
                            </div>
                        </div>
                        <div class="col-lg-3 col-12 foot1">
                            <div class="footer-logo text-center">
                                <a href="#tawakkalna_section_1"><img src="../assets/logo.svg" alt=""
                                        class="img-fluid" title="" /></a>
                                <a href="https://sdaia.gov.sa/" class="px-2 d-block sdaia-logo" target="_blank"><img src="../assets/sdaia.svg" alt=""
                                        class="img-fluid mt-4" /></a>
                            </div>
                        </div>
                        <!--<div class="col-lg-3 col-12 foot3">
                            <div class="footer-block">
                                 <ul class="contact-info">
                                    <li><a href="https://twitter.com/TawakkalnaApp" target="_blank">@TawakkalnaApp <i class="fab fa-twitter"></i></a></li>
                                    <li><a href="javascript:;">800128999 <i class="fas fa-phone-alt"></i></a></li>

                                </ul>
                            </div>
                        </div>-->
                        
                    </div>

                </div>
            </div>
            <div class="copyrights">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <div class="copyright-content text-center">
                                <p> © جميع الحقوق محفوظة، سدايا، 2020 </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*--- footer --- */
 footer {
	position: relative;
	background: #f8fbff;
	border-top: 1px solid rgba(214, 217, 222, .1);
}
 footer .footer-logo {
	margin-top: 40px;
}
 footer .footer-logo img {
	display: block;
}
 footer .footer-block {
	padding: 50px 0 0 0;
}
 footer .footer-block ul {
	margin-bottom: 0;
	display: flex;
	flex-direction: column;
}
 footer .footer-block ul.contact-info li {
margin-right: 20px;
}
 footer .footer-block ul li {
list-style-type: none;
margin-bottom: 15px;
}
 footer .footer-block ul li a {
color: rgb(106, 114, 119);
line-height: 28px;
font-size: 16px;
position: relative;
transition: all 0.3s ease-out;
text-decoration: none;
}
 footer .footer-block ul li a i {
font-size: 20px;
color: red;
margin-left: 10px;
vertical-align: middle;
}
 footer .footer-block ul li a:hover {
transition: all 0.3s ease-out;
text-shadow: 0 0 0.65px #333, 0 0 0.65px black;
color: black;
}
 footer .download-apps {
padding: 50px 0 0 0;
}
 footer .download-apps label {
color: rgb(106, 114, 119);
display: block;
font-size: 16px;
margin-bottom: 20px;
}
 footer .download-apps img {
color: rgb(106, 114, 119);
line-height: 28px;
font-size: 16px;
position: relative;
transition: all 0.3s ease-out;
text-decoration: none;
margin-right: 10px;
}
 footer .download-apps img {
height: 35px;
}
 footer .download-apps img:hover {
opacity: 0.7;
cursor: pointer;
}
 footer .copyrights {
padding: 30px 0;
}
 footer .copyrights .copyright-content {
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
width: 100%;
}
 footer .copyrights p {
color: rgb(106, 114, 119);
font-size: 16px;
}
.sdaia-logo{
    width: 140px;
}
 
</style>
