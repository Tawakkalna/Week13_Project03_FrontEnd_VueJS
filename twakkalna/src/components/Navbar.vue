<template>
  <header>
            <div class="header-top">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <div class="header-container">
                                <!-- navigation start -->
                                <nav class="navbar navbar-expand w-100">
                                    <div class="navbar-toggler-container">
                                        <a class="navbar-toggler collapsed" href="#main-menu">
                                            <span class="icon-bar top-bar mt-0"></span>
                                            <span class="icon-bar middle-bar"></span>
                                            <span class="icon-bar bottom-bar"></span>
                                        </a>
                                    </div>
                                    <a class="navbar-brand" href="#tawakkalna_section_1"><img
                                            src="../assets/twlogo.png" alt="" title="الرئيسية" id="twlogo" /></a>
                                    <div class="collapse navbar-collapse" id="navbar">
                                        <div class="d-flex align-items-center justify-content-between w-100">
                                            <div class="main-menu" id="main-menu">
                                                <ul class="navbar-nav">
                                                    <li class="nav-item">
                                                        <a class="nav-link active"
                                                            href="#tawakkalna_section_1">الرئيسية</a>
                                                    </li>
                                                    <li class="nav-item">
                                                        <a class="nav-link" href="#tawakkalna_section_2">عن توكلنا</a>
                                                    </li>
                                                    <li class="nav-item">
                                                        <a class="nav-link" href="#offers">خدمات توكلنا</a>
                                                    </li>
                                                    <li class="nav-item">
                                                        <a class="nav-link" href="#tawakkalna_section_3">كيف يعمل
                                                            توكلنا</a>
                                                    </li>
                                                    <li class="nav-item">
                                                        <a class="nav-link" href="#tawakkalna_section_4">الأسئلة
                                                            الشائعة</a>
                                                    </li>
                                                    <li class="nav-item">
                                                        <a class="nav-link" href="#tawakkalna_section_5">تواصل معنا</a>
                                                    </li>
                                                </ul>
                                            </div>
                                            <ul class="navbar-nav">
                                                <li class="nav-item dropdown languages">
                                                    <a class="nav-link dropdown-toggle" href="javascript:;"
                                                        data-toggle="dropdown" aria-haspopup="true"
                                                        aria-expanded="false">
                                                        <span>العربية</span> <i class="fas fa-globe"></i>
                                                    </a>
                                                    <ul class="dropdown-menu">
                                                        <li><a class="dropdown-item" href="./en/index.html">English</a>
                                                        </li>
                                                        <li><a class="dropdown-item" href="./Urd/index.html">اوردو</a>
                                                        </li>
                                                    </ul>
                                                </li>
                                                <span class="nav-item twk-web">
                                                    <a href="https://tawakkalna.sdaia.gov.sa" class="nav-link "
                                                        target="_blank" id="login"> تسجيل الدخول
                                                        <img
                                                            src="../assets/arrow-left.png" alt=""
                                                            class="mr-3" id="arrow" /> </a>
                                                </span>
                                            </ul>
                                        </div>
                                    </div>
                                </nav>
                                <!-- navigation end -->
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </header>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


/* MAIN */
html,
body {
  overflow-x: hidden;
}

*:before,
*:after {
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

html,
body,
div,
span,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
abbr,
address,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
samp,
small,
strong,
sub,
sup,
var,
b,
i,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
 
}

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}

nav ul {
  list-style: none;
}

blockquote,
q {
  quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
  content: '';
  content: none;
}

a {
  margin: 0;
  padding: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
  text-decoration: none;
  -moz-transition: all 0.3s ease-out;
 
  -o-transition: all 0.3s ease-out;
  
  -webkit-transition: all 0.3s ease-out;
  
  transition: all 0.3s ease-out;
}

a,
a:hover,
a:active,
a:visited {
  text-decoration: none;
  outline: none;
}


ins {
  background-color: #ff9;
  color: #000;
  text-decoration: none;
}


mark {
  background-color: #ff9;
  color: #000;
  font-style: italic;
  font-weight: bold;
}

del {
  text-decoration: line-through;
}

abbr[title],
dfn[title] {
  border-bottom: 1px dotted;
  cursor: help;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}


hr {
  display: block;
  height: 1px;
  border: 0;
  border-top: 1px solid #cccccc;
  margin: 1em 0;
  padding: 0;
}

input,
select {
  vertical-align: middle;
}


h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'DINNextLTArabic-Bold';
}

ul,
ol {
 
  padding: 0px;
}

button {
  border: none;
}

li {
  list-style-type: none;
}

img {
  border: none;
  width: auto;
  height: auto;
}

header,
footer,
article,
content,
details,
section,
nav,
title,
clear {
  display: block;
}

.clear {
  clear: both;
}

::selection {
  color: #ffffff;
  background: #1FA99A;
}

::-moz-selection {
  color: #ffffff;
  background: #1FA99A;
}

::-webkit-input-placeholder {
  /* WebKit browsers */
  color: #516477 !important;
}

:-moz-placeholder {
  /* Mozilla Firefox 4 to 18 */
  color: #516477 !important;
}

::-moz-placeholder {
  /* Mozilla Firefox 19+ */
  color: #516477 !important;
}

:-ms-input-placeholder {
  /* Internet Explorer 10+ */
  color: #516477 !important;
}

::-webkit-input-placeholder {
  /* WebKit browsers */
  font-family: 'DINNextLTArabic-Regular' !important;
}

:-moz-placeholder {
  /* Mozilla Firefox 4 to 18 */
  font-family: 'DINNextLTArabic-Regular' !important;
}

::-moz-placeholder {
  /* Mozilla Firefox 19+ */
  font-family: 'DINNextLTArabic-Regular' !important;
}

:-ms-input-placeholder {
  /* Internet Explorer 10+ */
  font-family: 'DINNextLTArabic-Regular' !important;
}

body {
  font-size: 14px;
  direction: ltr;
  text-align: left;
  overflow-x: hidden;
  margin: 0;
  padding: 0;
  font-family: 'DINNextLTArabic-Regular';
  background: #ffffff;
}

#layout {
  position: relative;
  overflow: hidden;
  min-width: 400px;
}

#layout.fader:after {
  content: "";
  background: rgba(81, 100, 119, 0.6);
  position: absolute;
  z-index: 101;
  width: 100%;
  height: 100%;
  top: 0;
}

@media (min-width: 1360px) {
  .container {
    max-width: 1260px;
  }
  .container.wide {
    max-width: 1400px;
  }
  .container.narrow {
    max-width: 1040px;
  }
}

/* --------------------  Header --------------------*/
.header-top {
  position: relative;
  direction: rtl;
  display: flex;
  justify-content: center;
}



header {
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.09);
  background: #ffffff;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 999;
}

header .container {
  position: relative;
  z-index: 2;
}

.navbar {
  padding: 18px 0px;
  display: flex;
  align-items: center;
  width: 100%;
}

@media only screen and (min-width: 992px) and (max-width: 1199px) {
  .navbar {
    justify-content: space-between;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  .navbar {
    justify-content: space-between;
  }
}

@media only screen and (min-width: 545px) and (max-width: 767px) {
  .navbar {
    justify-content: space-between;
  }
}

@media only screen and (max-width: 544px) {
  .navbar {
    justify-content: space-between;
  }
}

.navbar .navbar-brand {
  display: inline-block;
  padding-top: 0;
  padding-bottom: 2px;
  margin-right: initial;
  line-height: inherit;
  color: #516477;
  font-size: 24px;
  margin-right: 30px;
  margin-left: 0;
}

.navbar .navbar-brand img {
  max-width: 280px;
}

.navbar .icon-bar {
  width: 21px;
  height: 3px;
  background-color: #1FA99A;
  display: block;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  margin-top: 4px;
}

.navbar .navbar-toggler:focus {
  outline: 0px;
}

.navbar .navbar-toggler .top-bar {
  transform: rotate(45deg);
  transform-origin: 10% 190%;
  background-color: #1FA99A;
}

.navbar .navbar-toggler .middle-bar {
  opacity: 0;
}

.navbar .navbar-toggler .bottom-bar {
  transform: rotate(-45deg);
  transform-origin: 10% -80%;
  background-color: #1FA99A;
}

.navbar .navbar-toggler.collapsed .top-bar {
  transform: rotate(0);
  background-color: #1FA99A;
}

.navbar .navbar-toggler.collapsed .middle-bar {
  opacity: 1;
}

.navbar .navbar-toggler.collapsed .bottom-bar {
  transform: rotate(0);
  background-color: #1FA99A;
}

.navbar .navbar-nav {
  margin-left: .5rem !important;
  margin-right: 0 !important;
}

.navbar .navbar-nav li.nav-item {
  margin: 5px 10px;
  align-items: center;
  justify-content: center;
  transition: all 0.2s ease-in;
  border-bottom: 2px solid transparent;
}

.navbar .navbar-nav li.nav-item .nav-link {
  font-size: 16px;
  color: #516477;
  padding: 10px 5px;
  white-space: normal;
  text-align: center;
  transition: all 0.2s ease-in;
}

.navbar .navbar-nav li.nav-item .nav-link::after {
  font-size: 18px;
}

.navbar .navbar-nav li.nav-item .nav-link:hover {
  color: #333E4B;
  text-shadow: 0 0 0.65px #333, 0 0 0.65px #333E4B;
}

.navbar .navbar-nav li.nav-item:hover, .navbar .navbar-nav li.nav-item.active {
  border-bottom: 2px solid #1FA99A;
}

.navbar .navbar-nav li.nav-item:hover a::after, .navbar .navbar-nav li.nav-item.active a::after {
  color: #1FA99A !important;
}

.navbar .navbar-nav li.nav-item.sdaia {
  border-bottom: none;
  margin-left: 20px;
}

.navbar .navbar-nav li.nav-item.sdaia img {
  height: 30px;
}

.navbar .navbar-nav li.nav-item.sdaia:hover {
  border-bottom: none;
  opacity: .8;
}

@media only screen and (min-width: 545px) and (max-width: 767px) {
  .navbar .navbar-nav li.nav-item.sdaia {
    display: none;
  }
}

@media only screen and (max-width: 544px) {
  .navbar .navbar-nav li.nav-item.sdaia {
    display: none;
  }
}

.navbar .navbar-nav li .nav-link:hover.dropdown-toggle::after {
  color: #DD4247;
}

.navbar .dropdown-toggle::after {
  margin-top: 3px;
  display: inline-block;
  width: 0;
  height: 0;
  vertical-align: -2px;
  content: "\f107";
  border-top: none;
  border-right: none;
  border-bottom: none;
  border-left: none;
  color: #516477;
  font-family: "Font Awesome\ 5 Free";
  font-weight: 900;
  margin-right: 6px;
  font-size: 13px;
}

.navbar .navbar-collapse.show .dropdown .dropdown-menu {
  background: #ebebeb;
}

.navbar .navbar-collapse.show .dropdown .dropdown-menu li .dropdown-item {
  border-bottom: 1px solid #dcdcdc;
  border-radius: 0px;
  background: transparent;
  color: #333E4B;
}

.navbar .navbar-collapse.show .dropdown .dropdown-menu li .dropdown-item:hover {
  color: #DD4247;
}

.navbar .navbar-collapse.show .dropdown .dropdown-menu li:last-child .dropdown-item {
  border-bottom: none;
}

.navbar .dropdown-menu {
  position: absolute;
  top: calc(100% - 10px);
  left: 0;
  z-index: 1000;
  float: left;
  min-width: 13rem;
  padding: 12px;
  margin: 18px 0px;
  font-size: 1rem;
  color: #ffffff;
  text-align: left;
  list-style: none;
  background-color: #ffffff;
  background-clip: padding-box;
  border: 1px solid #F8FBFF;
  border-radius: 4px;
  -webkit-box-shadow: 0px 3px 11px 0px rgba(0, 0, 0, 0.09);
  -moz-box-shadow: 0px 3px 11px 0px rgba(0, 0, 0, 0.09);
  box-shadow: 0px 3px 11px 0px rgba(0, 0, 0, 0.09);
}

@media only screen and (min-width: 545px) and (max-width: 767px) {
  .navbar .dropdown-menu {
    right: 0;
    left: auto;
  }
}

@media only screen and (max-width: 544px) {
  .navbar .dropdown-menu {
    right: 0;
    left: auto;
  }
}

.navbar .dropdown-item {
  display: block;
  width: 100%;
  padding: 15px 15px;
  clear: both;
  font-weight: 400;
  color: #516477;
  background-color: transparent;
  border: 0;
  font-size: 15px;
  line-height: 15px;
}

.navbar .dropdown-item:focus,
.navbar .dropdown-item:hover {
  text-decoration: none;
  background-color: #F0F3F9;
  border-radius: 4px;
  color: #333E4B;
  text-shadow: 0 0 0.65px #333, 0 0 0.65px #333E4B;
}

.navbar .dropdown-item:focus .dropdown-toggle::after,
.navbar .dropdown-item:hover.dropdown-toggle::after {
  color: #DD4247;
}

.dropdown-submenu {
  position: relative;
}

.dropdown-submenu a::after {
  transform: rotate(-90deg);
  position: absolute;
  right: 17px;
  top: 25px;
}

.dropdown-submenu .dropdown-menu {
  top: 0px;
  left: 100%;
  margin-left: 13px;
  margin-right: 0.1rem;
}

.caret-up {
  width: 0;
  height: 0;
  border-left: 4px solid rgba(0, 0, 0, 0);
  border-right: 4px solid rgba(0, 0, 0, 0);
  border-bottom: 4px solid;
  display: inline-block;
  margin-left: 2px;
  vertical-align: middle;
}

.mega-dropdown {
  position: unset;
}

.mega-dropdown-menu {
  width: 100%;
  position: absolute;
  top: 63px;
  margin: 15px 0px;
}

.mega-dropdown-menu ul {
  list-style: none;
}

.nav-dropitem-arrow {
  position: relative;
  font-size: 12px;
  opacity: 0;
  padding-right: 10px;
}

.nav-dropitem-arrow i {
  position: absolute;
  /* top: -1px;
      */
}

.dropdown-item:focus,
.dropdown-item:hover {
  color: #DD4247;
  text-decoration: none;
  background-color: #eeeffd;
  border-radius: 4px;
}

.dropdown-item:hover .nav-dropitem-arrow {
  color: #4955ef;
  opacity: 1;
  margin-right: 5px;
}

.navbar .navbar-toggler,
.navbar-boxed .navbar-toggler {
  padding: 0;
  font-size: 1.25rem;
  line-height: 1;
  border-radius: 0.25rem;
  position: relative;
  display: block;
}

/* mobile menu css */
.navbar-collapse.show .dropdown .dropdown-menu {
  background: #ffffff;
  box-shadow: none;
  margin: 7px 0px;
}

.navbar-collapse.show .dropdown .dropdown-menu .dropdown-submenu.dropdown-item {
  border-bottom: 1px solid #F8FBFF;
}

.navbar-boxed .navbar-collapse.show .dropdown .dropdown-menu {
  background: #ffffff;
  box-shadow: none;
  margin: 7px 0px;
}

.navbar-boxed .navbar-collapse.show .navbar-nav li .nav-link {
  border-bottom: 1px solid #F8FBFF;
}

.navbar-boxed .navbar-collapse.show .dropdown .dropdown-menu .dropdown-submenu.dropdown-item {
  border-bottom: 1px solid #F8FBFF;
}

.navbar-transparent .navbar-collapse.show .dropdown .dropdown-menu {
  background: #ffffff;
  box-shadow: none;
  margin: 7px 0px;
}

.navbar-transparent .navbar-collapse.show .navbar-nav li .nav-link {
  border-bottom: 1px solid #DD4247;
}

.navbar-transparent .navbar-collapse.show .dropdown .dropdown-menu .dropdown-submenu.dropdown-item {
  border-bottom: 1px solid #F8FBFF;
}

.navbar-nav li svg {
  fill: #333E4B;
  width: 22px;
  transition: all 0.2s ease-in;
  vertical-align: middle;
}

.navbar-nav li:hover svg {
  fill: #DD4247;
}

@media only screen and (max-width: 544px) {
  .dropdown.languages a span {
    display: none;
  }
}

@media (min-width: 992px) {
  .dropdown .dropdown-menu {
    display: block;
    visibility: hidden;
    opacity: 0;
    -webkit-transform: translateY(20px);
    -ms-transform: translateY(20px);
    transform: translateY(20px);
    -webkit-transition: all 0.3s ease-in;
    -o-transition: all 0.3s ease-in;
    transition: all 0.3s ease-in;
  }
  .dropdown:hover .dropdown-menu {
    visibility: visible;
    opacity: 1;
    -webkit-transform: scaleY(1);
    -ms-transform: scaleY(1);
    transform: scaleY(1);
    opacity: 1;
    visibility: visible;
  }
  .dropdown-submenu:hover .dropdown-menu {
    visibility: visible;
    opacity: 1;
    -webkit-transform: scaleY(1);
    -ms-transform: scaleY(1);
    transform: scaleY(1);
    opacity: 1;
    visibility: visible;
  }
}

@media (max-width: 991px) {
  .navbar-nav .dropdown-menu {
    position: static;
    float: none;
  }
  .dropdown-menu.show {
    display: block;
  }
}

/*--- MMenu --- */
@media only screen and (min-width: 992px) and (max-width: 1199px) {
  .main-menu {
    display: none;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  .main-menu {
    display: none;
  }
}

@media only screen and (min-width: 545px) and (max-width: 767px) {
  .main-menu {
    display: none;
  }
}

@media only screen and (max-width: 544px) {
  .main-menu {
    display: none;
  }
}

@media only screen and (min-width: 992px) and (max-width: 1199px) {
  #mm-main-menu {
    display: block;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  #mm-main-menu {
    display: block;
  }
}

@media only screen and (min-width: 545px) and (max-width: 767px) {
  #mm-main-menu {
    display: block;
  }
}

@media only screen and (max-width: 544px) {
  #mm-main-menu {
    display: block;
  }
}

.navbar-toggler-container {
  display: none;
}

@media only screen and (min-width: 992px) and (max-width: 1199px) {
  .navbar-toggler-container {
    display: block;
  }
}

@media only screen and (min-width: 768px) and (max-width: 991px) {
  .navbar-toggler-container {
    display: block;
  }
}

@media only screen and (min-width: 545px) and (max-width: 767px) {
  .navbar-toggler-container {
    display: block;
  }
}

@media only screen and (max-width: 544px) {
  .navbar-toggler-container {
    display: block;
  }
}

.mm-navbars_top {
  display: none;
}

.navbar-expand .navbar-collapse {
  flex-basis: auto;
  flex-grow: initial;
}

@media only screen and (min-width: 1200px) {
  .navbar-expand .navbar-collapse {
    width: 100%;
  }
}

.twk-web{
    background-image: linear-gradient(70deg, rgb(131, 22, 37) 0%, rgb(218, 49, 69) 100%);
    background-color: rgba(0,0,0,0);
    background-clip: border-box;
    align-items: center;
    border-radius: 100px;
    box-shadow: rgba(199, 199, 199, 0.79) 0px 3px 11px -1px;
    box-sizing: border-box;
    font-family:  "DINNextLTArabic-Regular";
    direction: rtl;
    font-size: 14px;
    font-weight: 400;
    height: 50px;
    justify-content: center;
    line-height: 21px;
    width: 180px;
    margin: 5px 10px 10px 5px;
    text-align: right;
    position: relative; 
}

#login{
    position: absolute;
    top: 50%;
    transform: translate(0, -50%);
    margin-right: 15px;
    background-attachment: scroll;
    list-style-position: outside;
    text-align: center;
    outline-color: rgb(255, 255, 255);
    text-decoration: rgb(255, 255, 255);
    text-decoration-color: rgb(255, 255, 255);
    text-decoration-style: solid;
    transition-duration: 0.4s;
    transition-property: all;
    color: rgb(255, 255, 255);
    vertical-align: baseline;
    white-space: normal
}

#login:hover{
    font-size: 16px;
    
}

#arrow{
    height: 10%;
    width: 15%;
    vertical-align: middle;
    border-style: none;
    margin-right: 16px;
}

#twlogo{
    width: 80%;
}

</style>
