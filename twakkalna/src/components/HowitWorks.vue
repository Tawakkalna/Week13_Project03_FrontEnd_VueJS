<template>
  <div class="container text-end">
    <h1 class="header fw-bold my-5">كيف يعمل توكلنا؟</h1>
    <div class="fw-bold fs-2 mb-3" style="color: #323e4a">
      خطوات التسجيل في توكلنا
    </div>
    <div style="color: #707e8c">هل لديك حساب في أبشر؟</div>

    <div class="row">
      <div class="col-6 options">
        <button type="button" class="acc-btns selected" @click="haveAcc">
          لدي حساب أبشر
        </button>
        <button type="button" class="acc-btns" @click="dontHaveAcc">
          ليس لدي حساب أبشر
        </button>
        <button type="button" class="acc-btns">تسجيل الزائرين</button>
      </div>
      <div class="col-6">
        <span id="noacc">
          إذا لم تكن مسجلًا في نظام أبشر، فإن تسجيلك في تطبيق توكلنا يتطلب
          <strong> تزكيتك من خلال أحد المسجلين </strong> في أبشر عبر خدمة تعريف
          رقم الجوال لتطبيق توكلنا المدرجة ضمن خدمات المنصة، حيث يمكن الوصول
          إليها عبر الطريقة التالية:
        </span>
      </div>
    </div>

    <div class="row steps container w-75 m-auto">
      <div class="col d-flex flex-column align-items-center">
        1
        <img class="arrow" src="../images/steps/step.png" alt="step1" />
        <div class="step-image">
          <img src="../images/steps/favicon.png" alt="step1" />
        </div>
        <div class="step-text">حمل التطبيق</div>
      </div>
      <div class="col d-flex flex-column align-items-center">
        2
        <img
          class="arrow upsidedown"
          src="../images/steps/step.png"
          alt="step1"
        />
        <div class="step-image">
          <img src="../images/steps/step2.png" alt="step1" />
        </div>
        <div class="step-text">تسجيل مستخدم جديد وإدخال المعلومات المطلوبة</div>
      </div>
      <div class="col d-flex flex-column align-items-center">
        3
        <img class="arrow" src="../images/steps/step.png" alt="step1" />
        <div class="step-image">
          <img src="../images/steps/step3.png" alt="step1" />
        </div>
        <div class="step-text">
          سيصلك رمز التحقق على جوالك المسجّل في أبشر لتفعيل الحساب
        </div>
      </div>
      <div class="col d-flex flex-column align-items-center">
        4
        <img
          class="arrow upsidedown"
          src="../images/steps/step.png"
          alt="step1"
        />
        <div class="step-image">
          <img src="../images/steps/step4.png" alt="step1" />
        </div>
        <div class="step-text">
          حدّد مكان إقامتك على الخريطة بشكل دقيق وأجب عن الأسئلة الصحية
        </div>
      </div>
      <div class="col d-flex flex-column align-items-center">
        5
        <div class="step-image">
          <img src="../images/steps/step5.png" alt="step1" />
        </div>
        <div class="step-text">
          حدد التابعين والمكفولين الموجودين في نفس مكان إقامتك (عائلة، عمال
          منزليون)
        </div>
      </div>

      <br />
    </div>
      <Tutorial />
  </div>
</template>
<script>
import $ from "jquery";
import Tutorial from "./Tutorial.vue";

export default {
  name: "HowitWorks",
  components: {
    Tutorial,
  },
  methods: {
    dontHaveAcc() {
      $("#noacc").show(333);
      $(".selected").removeClass("selected");
      $("button:nth-of-type(2)").addClass("selected");
    },
    haveAcc() {
      $("#noacc").hide(333);
      $(".selected").removeClass("selected");
      $("button:nth-of-type(1)").addClass("selected");
    },
  },
  data() {
    return {};
  },
  mounted() {
    $("#noacc").hide();
  },
};
</script>
<style scoped>
.header {
  color: #1fa99b;
  text-align: center;
}
.acc-btns {
  color: gray;
  padding: 10px 30px;
  font-size: 16px;
  margin: 15px 0;
  margin-left: 10px;
  border-radius: 32px;
  background-color: white;
  border: 1px solid gray;
}
.acc-btns:hover {
  background-color: #dd4247;
  color: white;
  border: 1px solid #dd4247;
}
.selected {
  color: #ffffff;
  border: 1px solid #dd4247;
  background: #dd4247;
}
.step-image img {
  margin: auto;
  height: 50px;
}

.step-image {
  display: flex;
  background: rgba(31, 169, 154, 0.15);
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin: 25px 0px;
  transition: transform 0.5s;
}
.step-image:hover{
  transform: rotateY(180deg);
}
.step-text {
  color: #3b444d;
  text-align: center;
  font-weight: bold;
  font-size: 20px;
  transition: color 0.5s;
}
.step-text:hover {
  color: #109785;
}
.arrow {
  height: 20px;
  top: 40px;
  right: 141px;
  position: absolute;
}
.steps div {
  position: relative;
}
#noacc {
  font-size: 18px;
}
.upsidedown {
  transform: rotate(180deg);
  top: 120px;
}

@media only screen and (max-width: 1200px) {
  .arrow {
  height: 20px;
  top: 40px;
  right: 125px;
  position: absolute;
  }
  .upsidedown {
  transform: rotate(180deg);
  top: 120px;
  }
}
</style>