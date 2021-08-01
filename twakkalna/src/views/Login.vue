<template>
  <div class="">
    <div dir="rtl" class="dropdown">
      <button  class="dropbtn"> عربي</button>
      
    </div>
    <div class="MainContainer">
      <img
        id="logo"
        src="../assets/twlogo.png"
        alt="tawakkalna logo"
      />

      <div dir="rtl" class="card">
        <div class="container">
          <div class="textDiv">
            <div class="col-auto">
              <h5>تسجيل الدخول</h5>
            </div>
            <div class="col-auto">
              <p class="fs--1 text-600 mb-0">
                <a href="/Account/Register">تسجيل جديد</a>
              </p>
            </div>
          </div>
          <form @submit.prevent="login">
            <div>
              <input
                placeholder="رقم الھویة الوطنیة/ هوية مقيم/ رقم الجوال"
                type="text"
              />
            </div>
            <div>
              <input type="password" placeholder="كلمة المرور" />
            </div>
            <div class="second">
              <div class="textInnerDiv">
                <div class="custom-control custom-checkbox">
                  <input
                    class="custom-control-input"
                    type="checkbox"
                    id="basic-checkbox"
                    checked="checked"
                    data-val="true"
                    data-val-required="The RememberMe field is required."
                    name="RememberMe"
                    value="true"
                  />
                  <label class="custom-control-label" for="basic-checkbox"
                    >تذكرنى</label
                  >
                </div>
              </div>

              <a class="fs--1" href="/Account/ForgotPassword"
                >نسيت كلمة المرور</a
              >
            </div>
             <!-- <router-link to="/details"> login </router-link>
             <router-view/> -->
            <button
              class="btn btn-primary btn-block mt-3"
              type="submit"
              name="submit"
            >
              التالي
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import axios from 'axios';

export default {
  name: "LoginPage",
  props: {
    msg: String,
  },
  methods: {
    login: function(e) {
      const loginDetails = {
        national_id: "1099664582",
        password: "secret"
      };

      axios.post('http://tawakalna.maneea.net/api/login', loginDetails)
      .then((response) => {
        localStorage.setItem("token", response.data.token);
        this.$router.push("/details");
      })
      .catch(function (error) {
        console.log(error);
      });
      
      e.preventDefault();
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.MainContainer {
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
  align-content: center !important;
  flex-direction: column;
  justify-content: space-between;
  padding-top: 50px;
}

#logo {
  height: 73px;
  width: 200px;
  margin-bottom: 30px;
}

.card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
}

/* On mouse-over, add a deeper shadow */

/* Add some padding inside the card container */
.container {
  width: 350px;
  height: 300px;
  padding: 48px;
}

.textDiv {
  display: flex !important;
  justify-content: space-between;
}
input {
  width: 100%;
  height: calc(1.5em + 0.625rem + 2px);
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #344050;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #d8e2ef;
  border-radius: 0.25rem;
  margin-bottom: 10px;
}


.textInnerDiv {
  display: flex;
  justify-content: space-around;
  flex-direction: row;
}

#basic-checkbox {
  height: 16px;
  width: 16px;
}

.second {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
}

a {
  color: #2cafa1;
}

button {
  background-color: #2eafa1;
  border-color: #2eafa1;
  width: 100%;
  height: 36px;
  border-radius: 0.25rem;
  color: rgb(255, 255, 255);
  margin-top: 10px;
}

/* Dropdown Button */
.dropbtn {
  background-color: #ffffff;
  color: #04AA6D;
  font-size: 16px;
  border: none;
  width: 70px;
}

/* The container <div> - needed to position the dropdown content */
.dropdown {
  position: relative;
  display: inline-block;
   display: flex;
   flex-direction: row;

}

/* Dropdown Content (Hidden by Default) */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {background-color: #ddd;}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {display: block;}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover .dropbtn {background-color: #ffffff;}
/* ----------- */

</style>
