<template>
   <section class="about" id="tawakkalna_section_2">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-12 order-2" data-aos="fade-left" data-aos-duration="500">
                    <article id="content">
                        <h2 class="title">عن توكلنا</h2>
                        <p class="textJustify">
                            انطلاقًا من حرص حكومة المملكة العربية السعودية -أيدها الله- على الحفاظ على صحة
                            وسلامة المواطنين والمقيمين على أراضيها من خطر انتشار فيروس كورونا المستجد؛ قامت
                            الهيئة السعودية للبيانات والذكاء الاصطناعي "سدايا" بإطلاق تطبيق "توكلنا"، وذلك
                            لمساندة الجهود
                            الحكومية لمواجهة فيروس كورونا.
                        </p>
                        <p class="textJustify">
                            هدف تطبيق "توكلنا" في بدايته إلى المساهمة في إدارة عملية منح التصاريح إلكترونيًا
                            خلال فترة منع التجول، وذلك لمنسوبي القطاعات الحكومية، ومنسوبي القطاع الخاص، بالإضافة
                            إلى الأفراد، بالتعاون مع وزارة الصحة وعدد من الجهات الحكومية خلال فترة المنع
                            المفروضة، مما ساعد في الحد من انتشار فيروس كورونا في المملكة.
                        </p>
                        <p class="textJustify">
                            وخلال مرحلة العودة بحذر، ورفع إجراءات المنع، أطلق التطبيق عِدّة خدمات جديدة مهمة
                            تساهم في تحقيق العودة الآمنة، أبرزها توضيح الحالة الصحية لمستخدم التطبيق من خلال
                            الأكواد المُلوَّنة بأعلى درجات الأمان والخصوصيَّة.
                        </p>
                        <p class="textJustify">
                            ولأن مواجهة جائحة كورونا تتطلب تظافر جهود الدولة والمجتمع، فقد أتاح تطبيق "توكلنا"
                            للأفراد المساهمة في ذلك من خلال الإبلاغ عن الأفراد والتجمعات المخالفة للإجراءات
                            الاحترازية المعمول بها، إلى جانب الإبلاغ عن حركة الدخول إلى الأحياء الممنوعة، والتي
                            عزلت بناء على تقدير الجهات المعنية.
                        </p>
                    </article>
                   
                </div>
                <div class="col-lg-6 col-12 about-app" data-aos="zoom-in" data-aos-duration="500">
                    <img src="../assets/about-image.png" class="img-fluid" alt="" />
                </div>
            </div>
        </div>
    </section>
</template>


<script>
export default {
  name: 'About'
}
</script>


<style scoped>
.container {
    position: relative;
    z-index: 3;
    
}
.about article {
    overflow: hidden;
}

.title {
    display: flex;
    color: #1FA99A;
    font-size: 40px;
    font-weight: bold;
    margin-bottom: 30px;
   
}

.textJustify{
    text-align: justify;
}

.mainBtn {
    border-radius: 5px;
    color: #1FA99A;
    margin: 0;
    -webkit-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out;
    display: inline-block;
    font-size: 20px;
    margin-top: 20px;
}

.about h4 {
    font-size: 24px;
    color: #333E4B;
    margin-top: 30px;
    margin-bottom: 10px;
}

.about p {
    font-size: 20px;
    line-height: 36px;
    color: #333E4B;
}

.about.inner p {
    font-size: 18px;
    color: #516477;
}

.about .about-app {
    -webkit-box-ordinal-group: 4;
    -moz-box-ordinal-group: 4;
    -ms-flex-order: 3;
    order: 3;
}

.about img {
    margin-bottom: 20px;
}

</style>

