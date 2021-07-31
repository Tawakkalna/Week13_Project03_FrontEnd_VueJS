<template>
  <div class="faq-container">
    <h1 class="faq-header">الأسئلة الشائعة</h1>
    <nav dir="rtl" class="container">
      <div
        class="nav nav-tabs justify-content-center"
        id="nav-tab"
        role="tablist"
      >
        <button
          class="nav-link tap-text active"
          id="nav-home-tab"
          data-bs-toggle="tab"
          data-bs-target="#nav-home"
          type="button"
          role="tab"
          aria-controls="nav-home"
          aria-selected="true"
        >
          &ensp; عام &ensp;
        </button>
        <button
          class="nav-link tap-text"
          id="nav-download-tab"
          data-bs-toggle="tab"
          data-bs-target="#nav-download"
          type="button"
          role="tab"
          aria-controls="nav-download"
          aria-selected="false"
        >
          &ensp; تحميل التطبيق &ensp;
        </button>
        <button
          class="nav-link tap-text"
          id="nav-signin-tab"
          data-bs-toggle="tab"
          data-bs-target="#nav-signin"
          type="button"
          role="tab"
          aria-controls="nav-signin"
          aria-selected="false"
        >
          &ensp; التسجيل والدخول &ensp;
        </button>
        <button
          class="nav-link tap-text"
          id="nav-edit-tab"
          data-bs-toggle="tab"
          data-bs-target="#nav-edit"
          type="button"
          role="tab"
          aria-controls="nav-edit"
          aria-selected="false"
        >
          &ensp; تعديل البيانات الشخصية &ensp;
        </button>
        <button
          class="nav-link tap-text"
          id="nav-services-tab"
          data-bs-toggle="tab"
          data-bs-target="#nav-services"
          type="button"
          role="tab"
          aria-controls="nav-services"
          aria-selected="false"
        >
          &ensp;خدمات التطبيق &ensp;
        </button>
      </div>
    </nav>
    <div class="tab-content allall" id="nav-tabContent">
      <div
        class="tab-pane all-faq fade show active"
        id="nav-home"
        role="tabpanel"
        aria-labelledby="nav-home-tab"
      >
        <div class="faq">
          <div
            class=" card faq-card"
            style="border-radius: 10px; border-width: 0; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.1), 0 6px 20px 0 rgba(0, 0, 0, 0.1);"
          >
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>ما هي خاصية تقديم طلب الحصول على لقاح كورونا؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseOne"
                  aria-expanded="false"
                  aria-controls="collapseOne"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseOne">
                  <div class="card card-body">
                    <p class="answer card-text">
                      تتيح لك هذه الخاصية التقديم على طلب الحصول على لقاح
                      كورونا، وذلك بتعبئة استمارة تقديم طلب الحصول على لقاح
                      كورونا التي تطلب معلومات شخصية ومعلومات العمل ومعلومات
                      صحية.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div
            class=" card faq-card"
            style="border-radius: 10px; border-width: 0; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.1), 0 6px 20px 0 rgba(0, 0, 0, 0.1);"
          >
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>كيف يمكنني تقديم طلب الحصول على لقاح كورونا؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseTow"
                  aria-expanded="false"
                  aria-controls="collapseTow"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseTow">
                  <p class="answer card-text">
                    من الصفحة الرئيسة اختر (الخدمات).
                    <br />من قائمة (خدمات الصحة) اختر (لقاح كورونا). <br />يمكنك
                    استعراض بطاقات المستفيدين. <br />اختر (تقديم طلب).
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="faq-card card " style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  هل بإمكاني تقديم طلب الحصول على لقاح كورونا لأحد التابعين لدي؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseThree"
                  aria-expanded="false"
                  aria-controls="collapseThree"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseThree">
                  <p class="answer card-text">
                    نعم يمكنك تقديم طلب الحصول على لقاح كورونا لأحد التابعين أو
                    المكفولين.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلب الحصول على اللقاح لأحد التابعين غير ظاهر، ماذا أفعل؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFour"
                  aria-expanded="false"
                  aria-controls="collapseFour"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFour">
                  <p class="answer card-text">
                    إما أن التابع قد قام بالتقديم مسبقاً، أو أنه ليس من الفئة
                    ذات الأولوية.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلبت الحصول على لقاح كورونا ولكن لا يمكنني استعراض الطلب؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFive"
                  aria-expanded="false"
                  aria-controls="collapseFive"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFive">
                  <p class="answer card-text">
                    في حال تم تقديم الطلب وكان لايزال تحت المعالجة ستعرض الحالة
                    وتاريخ التقديم فقط، وفي حال عدم ظهورهما يرجى التواصل مع خدمة
                    العملاء.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="tab-pane all-faq fade"
        id="nav-download"
        role="tabpanel"
        aria-labelledby="nav-download-tab"
      >
        <div class="faq">
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>ما هي أنظمة التشغيل التي يتوفر فها تطبيق "توكلنا"؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseOne"
                  aria-expanded="false"
                  aria-controls="collapseOne"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseOne">
                  <div class="card card-body">
                    <p class="answer card-text">
                      التطبيق يتوفر حالياً فقط لأنظمة تشغيل أبل iOS (الإصدار
                      10.0 وأعلى) وأنظمة تشغيل أندرويد Android (الإصدار 6.0
                      وأعلى).
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>ما هي الأجهزة التي يتوفر فيها تطبيق "توكلنا"؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseTow"
                  aria-expanded="false"
                  aria-controls="collapseTow"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseTow">
                  <div class="card card-body">
                    <p class="answer card-text">
                      أجهزة الآيفون ويتم تحميله من متجر أبل App Store.
                      <br />
                      وأجهزة الأندرويد ويتم تحميله من متجر جوجل بلاي Google
                      Play.
                      <br />
                      وأجهزة هواوي ويتم تحميله من متجر App Gallery.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  هل ممكن تحميل تطبيق "توكلنا" من أماكن أخرى غير متجر أبل
                  AppStore أو متجر جوجل بلاي Google Play؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseThree"
                  aria-expanded="false"
                  aria-controls="collapseThree"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseThree">
                  <div class="card card-body">
                    <p class="answer card-text">
                      يتوفر التطبيق أيضا لمستخدمي أجهزة هواوي ويمكن تحميله من
                      متجر App Gallery، كما أن التطبيق متوفر كذلك في المتاجر
                      الرسمية وهي متجر أبل App Store أو متجر جوجل بلاي Google
                      Play.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلب الحصول على اللقاح لأحد التابعين غير ظاهر، ماذا أفعل؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFour"
                  aria-expanded="false"
                  aria-controls="collapseFour"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFour">
                  <p class="answer card-text">
                    إما أن التابع قد قام بالتقديم مسبقاً، أو أنه ليس من الفئة
                    ذات الأولوية.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلبت الحصول على لقاح كورونا ولكن لا يمكنني استعراض الطلب؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFive"
                  aria-expanded="false"
                  aria-controls="collapseFive"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFive">
                  <p class="answer card-text">
                    في حال تم تقديم الطلب وكان لايزال تحت المعالجة ستعرض الحالة
                    وتاريخ التقديم فقط، وفي حال عدم ظهورهما يرجى التواصل مع خدمة
                    العملاء.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="tab-pane all-faq fade"
        id="nav-signin"
        role="tabpanel"
        aria-labelledby="nav-signin-tab"
      >
        <div class="faq">
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>ما هي خاصية تقديم طلب الحصول على لقاح كورونا؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseOne"
                  aria-expanded="false"
                  aria-controls="collapseOne"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseOne">
                  <div class="card card-body">
                    <p class="answer card-text">
                      تتيح لك هذه الخاصية التقديم على طلب الحصول على لقاح
                      كورونا، وذلك بتعبئة استمارة تقديم طلب الحصول على لقاح
                      كورونا التي تطلب معلومات شخصية ومعلومات العمل ومعلومات
                      صحية.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>كيف يمكنني تقديم طلب الحصول على لقاح كورونا؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseTow"
                  aria-expanded="false"
                  aria-controls="collapseTow"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseTow">
                  <p class="answer card-text">
                    من الصفحة الرئيسة اختر (الخدمات).
                    <br />من قائمة (خدمات الصحة) اختر (لقاح كورونا). <br />يمكنك
                    استعراض بطاقات المستفيدين. <br />اختر (تقديم طلب).
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  هل بإمكاني تقديم طلب الحصول على لقاح كورونا لأحد التابعين لدي؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseThree"
                  aria-expanded="false"
                  aria-controls="collapseThree"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseThree">
                  <p class="answer card-text">
                    نعم يمكنك تقديم طلب الحصول على لقاح كورونا لأحد التابعين أو
                    المكفولين.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلب الحصول على اللقاح لأحد التابعين غير ظاهر، ماذا أفعل؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFour"
                  aria-expanded="false"
                  aria-controls="collapseFour"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFour">
                  <p class="answer card-text">
                    إما أن التابع قد قام بالتقديم مسبقاً، أو أنه ليس من الفئة
                    ذات الأولوية.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلبت الحصول على لقاح كورونا ولكن لا يمكنني استعراض الطلب؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFive"
                  aria-expanded="false"
                  aria-controls="collapseFive"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFive">
                  <p class="answer card-text">
                    في حال تم تقديم الطلب وكان لايزال تحت المعالجة ستعرض الحالة
                    وتاريخ التقديم فقط، وفي حال عدم ظهورهما يرجى التواصل مع خدمة
                    العملاء.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="tab-pane all-faq fade"
        id="nav-edit"
        role="tabpanel"
        aria-labelledby="nav-edit-tab"
      >
        <div class="faq">
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>ما هي أنظمة التشغيل التي يتوفر فها تطبيق "توكلنا"؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseOne"
                  aria-expanded="false"
                  aria-controls="collapseOne"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseOne">
                  <div class="card card-body">
                    <p class="answer card-text">
                      التطبيق يتوفر حالياً فقط لأنظمة تشغيل أبل iOS (الإصدار
                      10.0 وأعلى) وأنظمة تشغيل أندرويد Android (الإصدار 6.0
                      وأعلى).
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>ما هي الأجهزة التي يتوفر فيها تطبيق "توكلنا"؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseTow"
                  aria-expanded="false"
                  aria-controls="collapseTow"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseTow">
                  <div class="card card-body">
                    <p class="answer card-text">
                      أجهزة الآيفون ويتم تحميله من متجر أبل App Store.
                      <br />
                      وأجهزة الأندرويد ويتم تحميله من متجر جوجل بلاي Google
                      Play.
                      <br />
                      وأجهزة هواوي ويتم تحميله من متجر App Gallery.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  هل ممكن تحميل تطبيق "توكلنا" من أماكن أخرى غير متجر أبل
                  AppStore أو متجر جوجل بلاي Google Play؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseThree"
                  aria-expanded="false"
                  aria-controls="collapseThree"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseThree">
                  <div class="card card-body">
                    <p class="answer card-text">
                      يتوفر التطبيق أيضا لمستخدمي أجهزة هواوي ويمكن تحميله من
                      متجر App Gallery، كما أن التطبيق متوفر كذلك في المتاجر
                      الرسمية وهي متجر أبل App Store أو متجر جوجل بلاي Google
                      Play.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلب الحصول على اللقاح لأحد التابعين غير ظاهر، ماذا أفعل؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFour"
                  aria-expanded="false"
                  aria-controls="collapseFour"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFour">
                  <p class="answer card-text">
                    إما أن التابع قد قام بالتقديم مسبقاً، أو أنه ليس من الفئة
                    ذات الأولوية.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلبت الحصول على لقاح كورونا ولكن لا يمكنني استعراض الطلب؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFive"
                  aria-expanded="false"
                  aria-controls="collapseFive"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFive">
                  <p class="answer card-text">
                    في حال تم تقديم الطلب وكان لايزال تحت المعالجة ستعرض الحالة
                    وتاريخ التقديم فقط، وفي حال عدم ظهورهما يرجى التواصل مع خدمة
                    العملاء.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="tab-pane all-faq fade"
        id="nav-services"
        role="tabpanel"
        aria-labelledby="nav-services-tab"
      >
        <div class="faq">
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>ما هي خاصية تقديم طلب الحصول على لقاح كورونا؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseOne"
                  aria-expanded="false"
                  aria-controls="collapseOne"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseOne">
                  <div class="card card-body">
                    <p class="answer card-text">
                      تتيح لك هذه الخاصية التقديم على طلب الحصول على لقاح
                      كورونا، وذلك بتعبئة استمارة تقديم طلب الحصول على لقاح
                      كورونا التي تطلب معلومات شخصية ومعلومات العمل ومعلومات
                      صحية.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>كيف يمكنني تقديم طلب الحصول على لقاح كورونا؟</div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseTow"
                  aria-expanded="false"
                  aria-controls="collapseTow"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseTow">
                  <p class="answer card-text">
                    من الصفحة الرئيسة اختر (الخدمات).
                    <br />من قائمة (خدمات الصحة) اختر (لقاح كورونا). <br />يمكنك
                    استعراض بطاقات المستفيدين. <br />اختر (تقديم طلب).
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  هل بإمكاني تقديم طلب الحصول على لقاح كورونا لأحد التابعين لدي؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseThree"
                  aria-expanded="false"
                  aria-controls="collapseThree"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseThree">
                  <p class="answer card-text">
                    نعم يمكنك تقديم طلب الحصول على لقاح كورونا لأحد التابعين أو
                    المكفولين.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلب الحصول على اللقاح لأحد التابعين غير ظاهر، ماذا أفعل؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFour"
                  aria-expanded="false"
                  aria-controls="collapseFour"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFour">
                  <p class="answer card-text">
                    إما أن التابع قد قام بالتقديم مسبقاً، أو أنه ليس من الفئة
                    ذات الأولوية.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class=" card faq-card" style="border-radius: 10px;">
            <div class="card-body faq-card-body">
              <div class="card-title question">
                <div>
                  طلبت الحصول على لقاح كورونا ولكن لا يمكنني استعراض الطلب؟
                </div>
                <button
                  class="btn "
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFive"
                  aria-expanded="false"
                  aria-controls="collapseFive"
                >
                  <i class="bi bi-chevron-down"></i>
                </button>
              </div>
              <div>
                <div class="collapse" id="collapseFive">
                  <p class="answer card-text">
                    في حال تم تقديم الطلب وكان لايزال تحت المعالجة ستعرض الحالة
                    وتاريخ التقديم فقط، وفي حال عدم ظهورهما يرجى التواصل مع خدمة
                    العملاء.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FAQ",
};
</script>

<style>
.faq-container {
  padding: 7% 5%;
  background-color: #f8fbff;
}
.button [aria-selected="true"] {
  color: #1fa99a;
}
.faq-header {
  color: #1fa99a;
  font-weight: bolder;
  margin-bottom: 4%;
}
.tap-text {
  font-size: 25px;
  padding-left: 30px;
}
.allall {
  display: flex;
  justify-content: center;
}
.all-faq {
  width: 50vw;
  font-size: 20px;
}
.faq {
  display: flex;
  justify-content: end;
  flex-direction: column;
  margin: 20px 0;
}
.faq-card {
  padding: 10px;
  margin-bottom: 20px;
  border-radius: 10px;
  border-width: 0;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.1), 0 6px 20px 0 rgba(0, 0, 0, 0.1);
}
.faq-card-body {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  direction: rtl;
}
.question {
  font-weight: bolder;
  padding-bottom: 2%;
  display: flex;
  justify-content: space-between;
  width: 100%;
}
.answer {
  text-align: justify;
}
.center {
  text-align: center;
}

@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css");
</style>
