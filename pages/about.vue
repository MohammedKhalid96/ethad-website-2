<template>
  <div class="internal-page">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item">
          <nuxt-link to="/" class="no-line">الرئيسية</nuxt-link>
        </li>
        <li class="breadcrumb-item active" aria-current="page">رؤيتنا</li>
      </ol>
    </nav>

    <section id="about-section-id" class="about-section section">
      <div class="big-padding">
        <div class="row no-gutters">
          <div class="col-md-4 d-flex align-items-center">
            <div class="about-right relative">
              <div class="about-removable-overlay absolute"></div>
              <div class="about-side-caption">
                <h3 class="about-title-h3 orange">تاريخنا</h3>
                <p class="about-title-sub-p white">
                  الجودة والارادة مع خدماتنا !
                </p>
                <p class="about-title-p white">
                  مشاريع سكنية وإدارية وتجارية ورياضية وترفيهية يقدمها لك
                  الاتحاد بتصاميم إبداعية ومبتكرة غير مسبوقة يهتم الاتحاد بأنماط
                  الحياة العصرية الراقية لذا صمم لك مجموعات عقارية بمختلف
                  الديكورات والتشطيبات والتي يتم تسليمها لك في الوقت المحدد
                </p>
                <p class="about-title-p white">
                  تمتع بأفضل الوحدات السكنية بأنظمة اقتصادية تناسب جميع الشرائح
                  المختلفة لتختر منها ما يناسبك
                </p>
              </div>
            </div>
          </div>

          <div class="col-md-4">
            <div class="about-img">
              <img
                src="../static/images/slider-2-man.png"
                alt
                class="about-vector"
              />
            </div>
          </div>

          <div class="col-md-4 d-flex align-items-center">
            <div class="about-left relative">
              <div class="about-removable-overlay absolute"></div>
              <div class="about-side-caption">
                <h3 class="about-title-h3 orange">تجربة مختلفة واستثنائية</h3>
                <p class="about-title-sub-p white">
                  رؤيتنا في الاتحاد للاستثمار والتطوير العقاري
                </p>
                <p class="about-title-p white">
                  أن نصبح رائدين في مجال الاستثمار والتطوير العقاري في الشرق
                  الأوسط بأكمله وأن نكسب ونحافظ على رضا عملائنا من جميع أنحاء
                  العالم من خلال الخبرات البشرية المتعددة التي تعمل جاهدة للخروج
                  بأفضل جودة للوحدات السكنية وتقديم خدمات ما بعد البيع للعملاء
                </p>
                <p class="about-title-p white">
                  نتابع معك في خدمات ما بعد البيع لنتأكد من رضائك عن الجودة
                  العامة ومساعدتك في أي مشكلة قد تواجهك
                </p>
              </div>
            </div>
          </div>
        </div>

        <img
          src="../static/images/elithad-signature.png"
          alt
          class="signature"
        />

        <div class="action-link text-center relative">
          <nuxt-link to="/" class="link no-line">
            <span class="link-arrow">
              <font-awesome-icon icon="paper-plane"></font-awesome-icon>
            </span>
            تواصل معنا
          </nuxt-link>
        </div>
      </div>
    </section>
  </div>
</template>
