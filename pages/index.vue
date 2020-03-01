<template>
  <div class="home-page">
    <section class="home-intro relative">
      <div class>
        <div class="bg-video absolute">
          <video class="bg-video__content" width="100%" autoplay muted loop>
            <source src="../static/images/mp42.mp4" type="video/mp4" />
            <source src="../static/images/webm2.webm" type="video/webm" />
            Your browser is not supported!
          </video>
        </div>

        <div class="home-intro-overlay absolute">
          <div class="row no-gutters">
            <div class="col-1" v-for="i in 12" :key="i">
              <div :class="[`home-intro-overlay-col col-div-${i}`]"></div>
            </div>
          </div>
        </div>

        <!-- <div class="home-intro-caption-wrap">
          <div class="home-intro-desc absolute animated fadeInUp slow delay-8s">
            <h3 class="home-intro-title">
              <span class="home-intro-span">الاتحاد</span>
              نحن نبني حلمك
            </h3>
            <nuxt-link to="/" class="home-intro-link link">
              <span class="link-arrow">
                <font-awesome-icon icon="plus"></font-awesome-icon>
              </span>
              المزيد
            </nuxt-link>

            <nuxt-link to="/" class="home-intro-link link">
              <span class="link-arrow">
                <font-awesome-icon icon="paper-plane"></font-awesome-icon>
              </span>
              تواصل معنا
            </nuxt-link>
          </div>
        </div>-->
      </div>
    </section>

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

        <img src="../static/images/signature.png" alt class="signature" />
      </div>
    </section>

    <section class="services-section section">
      <div class="top-bottom-padding">
        <div class="row no-gutters">
          <div class="col-md-5">
            <div class="services-big-img">
              <img src="../static/images/2-blog.jpg" alt class="image-100" />
            </div>
          </div>

          <div class="col-md-7">
            <div class="services-caption mid-padding">
              <p class="small-caption white">
                معايير عالمي في مجال المقاولات الصناعية
              </p>
              <h3 class="services-title-h3 orange">الحل الأفضل للجميع</h3>
              <p class="services-caption white">
                مشاريع سكنية وإدارية وتجارية ورياضية وترفيهية يقدمها لك الاتحاد
                بتصاميم إبداعية ومبتكرة غير مسبوقة تجربة مختلفة واستثنائية في
                الاتحاد للاستثمار والتطوير العقاري مع أحدث الأساليب المتبعة في
                التخطيط والتصميم والتنفيذ والإدارة لتحصل على ما تريد بأفضل جودة
                ممكنة
              </p>

              <div class="services-slider">
                <carousel
                  :perPageCustom="[
                    [320, 1],
                    [768, 1],
                    [1024, 2]
                  ]"
                  :navigationEnabled="true"
                  :paginationEnabled="false"
                  :scrollPerPage="false"
                  :mouseDrag="false"
                  :loop="true"
                  :autoplay="true"
                  :speed="2000"
                  :autoplayTimeout="4000"
                  dir="rtl"
                >
                  <slide v-for="i in 6" :key="i">
                    <div class="service-box">
                      <nuxt-link to="/" class="no-line">
                        <div class="row no-gutters">
                          <div class="col-6">
                            <div class="service-img">
                              <img
                                src="../static/images/service-1.png"
                                alt
                                class="image-100"
                              />
                            </div>
                          </div>

                          <div class="col-6 d-flex align-items-center">
                            <div class="service-caption small-padding">
                              <h5 class="service-name white">
                                أنظمة دفع مختلفة
                              </h5>
                              <div
                                id="service-action-area"
                                class="action-link relative"
                              >
                                <span class="f-width-link link">
                                  <span class="link-arrow">
                                    <font-awesome-icon
                                      icon="plus"
                                    ></font-awesome-icon>
                                  </span>
                                  المزيد
                                </span>
                                <div class="frame top-frame-id"></div>
                                <div class="frame bottom-frame-id"></div>
                                <div class="frame left-frame-id"></div>
                                <div class="frame right-frame-id"></div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </nuxt-link>
                    </div>
                  </slide>
                </carousel>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="projects-section section">
      <div class="top-bottom-padding">
        <!-- <div class="title-circle"></div> -->
        <div class="row">
          <div class="col-md-3">
            <div class="project-box small-project-box" v-for="i in 2" :key="i">
              <nuxt-link to="/">
                <div class="project-img relative">
                  <img
                    src="../static/images/bg-new-4.jpg"
                    alt
                    class="image-100"
                  />

                  <div class="project-overlay absolute">
                    <div class="project-caption-overlay small-padding absolute">
                      <p class="project-name">
                        <font-awesome-icon icon="building"></font-awesome-icon
                        >كومبوند الجلاء العاصمة الادارية
                      </p>
                    </div>
                  </div>
                </div>
              </nuxt-link>
            </div>
          </div>

          <div class="col-md-6">
            <div class="project-box big-project-box">
              <nuxt-link to="/">
                <div class="project-img relative">
                  <img
                    src="../static/images/bg-new-4.jpg"
                    alt
                    class="image-100"
                  />

                  <div class="project-overlay absolute">
                    <div class="project-caption-overlay small-padding absolute">
                      <p class="project-name">
                        <font-awesome-icon icon="building"></font-awesome-icon
                        >كومبوند الجلاء العاصمة الادارية
                      </p>
                    </div>
                  </div>
                </div>
              </nuxt-link>
            </div>
          </div>

          <div class="col-md-3">
            <div class="project-box small-project-box" v-for="i in 2" :key="i">
              <nuxt-link to="/">
                <div class="project-img relative">
                  <img
                    src="../static/images/bg-new-4.jpg"
                    alt
                    class="image-100"
                  />

                  <div class="project-overlay absolute">
                    <div class="project-caption-overlay small-padding absolute">
                      <p class="project-name">
                        <font-awesome-icon icon="building"></font-awesome-icon
                        >كومبوند الجلاء العاصمة الادارية
                      </p>
                    </div>
                  </div>
                </div>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="test-section section">
      <div class="top-bottom-padding">
        <div class="test-section-bg">
          <div class="row no-gutters">
            <div class="col-md-8">
              <div class="test-section-slider">
                <carousel
                  :perPageCustom="[
                    [320, 1],
                    [768, 1],
                    [1024, 1]
                  ]"
                  :navigationEnabled="false"
                  :paginationEnabled="false"
                  :scrollPerPage="false"
                  :loop="true"
                  :autoplay="true"
                  :speed="2000"
                  :autoplayTimeout="4000"
                  dir="rtl"
                >
                  <slide v-for="i in 10" :key="i">
                    <img
                      src="../static/images/bg-new-4.jpg"
                      alt=""
                      class="image-100"
                    />
                  </slide>
                </carousel>
              </div>

              <div class="test-section-bottom-wrap">
                <div class="row no-gutters">
                  <div class="col-md-4">
                    <div class="test-section-action text-center">
                      <div class="test-section-action-link">
                        <nuxt-link to="/" class="no-line link-1">
                          <span class="link-arrow">
                            <font-awesome-icon icon="plus"></font-awesome-icon>
                          </span>
                          المزيد
                        </nuxt-link>
                      </div>

                      <div class="test-section-action-link">
                        <nuxt-link to="/" class="no-line link-2">
                          <span class="link-arrow">
                            <font-awesome-icon
                              icon="mobile-alt"
                            ></font-awesome-icon>
                          </span>
                          اتصل بنا
                        </nuxt-link>
                      </div>

                      <div class="test-section-action-link">
                        <nuxt-link to="/" class="no-line link-3 other-lang">
                          <span class="link-arrow">
                            <font-awesome-icon
                              icon="envelope"
                            ></font-awesome-icon>
                          </span>
                          info@ethad.com
                        </nuxt-link>
                      </div>
                    </div>
                  </div>

                  <div class="col-md-8">
                    <div class="test-section-caption mid-padding">
                      <h3 class="test-section-h3 orange">
                        معايير عالمي في مجال المقاولات الصناعية
                      </h3>
                      <p class="test-section-p">
                        مشاريع سكنية وإدارية وتجارية ورياضية وترفيهية يقدمها لك
                        الاتحاد بتصاميم إبداعية ومبتكرة غير مسبوقة تجربة مختلفة
                        واستثنائية في الاتحاد للاستثمار والتطوير العقاري مع أحدث
                        الأساليب المتبعة في التخطيط والتصميم والتنفيذ والإدارة
                        لتحصل على ما تريد بأفضل جودة ممكنة
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="test-section-side relative">
                <div class="test-section-caption mid-padding">
                  <h3 class="test-section-h3 orange">
                    معايير عالمي في مجال المقاولات الصناعية
                  </h3>
                  <p class="test-section-p">
                    مشاريع سكنية وإدارية وتجارية ورياضية وترفيهية يقدمها لك
                    الاتحاد بتصاميم إبداعية ومبتكرة غير مسبوقة تجربة مختلفة
                    واستثنائية في الاتحاد للاستثمار والتطوير العقاري مع أحدث
                    الأساليب المتبعة في التخطيط والتصميم والتنفيذ والإدارة لتحصل
                    على ما تريد بأفضل جودة ممكنة
                  </p>
                </div>

                <div class="test-section-bottom-side">
                  <div class="test-section-bottom-side-img">
                    <img
                      src="../static/images/h1-blog.jpg"
                      alt=""
                      class="image-100"
                    />
                  </div>
                  <div class="test-section-action text-center">
                    <div class="test-section-action-link">
                      <nuxt-link to="/" class="no-line">
                        <span class="link-arrow">
                          <font-awesome-icon icon="plus"></font-awesome-icon>
                        </span>
                        المزيد
                      </nuxt-link>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="blog-section section">
      <div class="top-bottom-padding">
        <div class="row no-gutters">
          <div class="col-md-3" v-for="i in 4" :key="i">
            <article class="blog-box">
              <nuxt-link to="/single-blog" class="no-line">
                <div class="blog-img relative">
                  <img :src="`./images/${i}-blog.jpg`" alt class="image-100" />

                  <div class="blog-caption-wrap small-padding absolute">
                    <div class="blog-caption-text-wrap small-padding absolute">
                      <div class="blog-insights">
                        <div class="blog-category">
                          <span class="blog-category-p white">العقارات</span>
                        </div>
                      </div>

                      <div class="home-blog-title">
                        <h3 class="home-blog-title-h3 white">
                          رؤيتنا في الاتحاد للاستثمار والتطوير العقاري
                        </h3>
                      </div>

                      <div class="home-blog-desc">
                        <p class="home-blog-title-p white">
                          أن نصبح رائدين في مجال الاستثمار والتطوير العقاري في
                          الشرق الأوسط بأكمله وأن نكسب ونحافظ على رضا عملائنا من
                          جميع أنحاء العالم
                        </p>
                      </div>

                      <div class="home-blog-action">
                        <div id="blog-action-area" class="action-link relative">
                          <span class="link">
                            <span class="link-arrow">
                              <font-awesome-icon
                                icon="plus"
                              ></font-awesome-icon>
                            </span>
                            المزيد
                          </span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </nuxt-link>
            </article>
          </div>
        </div>
      </div>
    </section>

    <section class="contact-section section">
      <div class="top-bottom-padding">
        <div class="row no-gutters">
          <div class="col-md-5">
            <div class="contact-map-img">
              <img
                src="../static/images/bg-new-4.jpg"
                alt=""
                class="image-100"
              />
            </div>
          </div>

          <div class="col-md-7">
            <div class="contact-side mid-padding">
              <div class="contact-section-form">
                <Form />
              </div>
              <div class="contact-info">
                <li>
                  <a class="no-line other-lang" href="tel:+0201004750956">
                    <font-awesome-icon icon="mobile-alt"></font-awesome-icon
                    >01004750956
                  </a>
                </li>

                <li>
                  <a class="no-line other-lang" href="tel:+0201004750956">
                    <font-awesome-icon icon="mobile-alt"></font-awesome-icon
                    >01004750956
                  </a>
                </li>

                <li>
                  <a class="other-lang no-line" href="mailto:info@ethad.com">
                    <font-awesome-icon icon="envelope"></font-awesome-icon
                    >info@ethad.com
                  </a>
                </li>

                <li>
                  <a class="no-line" target="_blank" href>
                    <font-awesome-icon icon="map-marker-alt"></font-awesome-icon
                    >ابراج رويال, السادس من اكتوبر, الجيزة
                  </a>
                </li>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import $ from "jquery";
import Form from "~/components/Form.vue";
export default {
  mounted: () => {
    $(window).scroll(function() {
      var hT = $("#service-action-area").offset().top,
        hH = $("#service-action-area").outerHeight(),
        wH = $(window).height(),
        wS = $(this).scrollTop();
      if (wS > hT + hH - wH && hT > wS && wS + wH > hT + hH) {
        $("#service-action-area .top-frame-id").addClass("top-frame");
        $("#service-action-area .left-frame-id").addClass("left-frame");
        $("#service-action-area .bottom-frame-id").addClass("bottom-frame");
        $("#service-action-area .right-frame-id").addClass("right-frame");
      }
    });

    $(window).scroll(function() {
      var hT = $("#blog-action-area").offset().top,
        hH = $("#blog-action-area").outerHeight(),
        wH = $(window).height(),
        wS = $(this).scrollTop();
      if (wS > hT + hH - wH && hT > wS && wS + wH > hT + hH) {
        $("#blog-action-area .top-frame-id").addClass("top-frame");
        $("#blog-action-area .left-frame-id").addClass("left-frame");
        $("#blog-action-area .bottom-frame-id").addClass("bottom-frame");
        $("#blog-action-area .right-frame-id").addClass("right-frame");
      }
    });

    // $(window).scroll(function() {
    //   var hT = $("#about-section-id").offset().top,
    //     hH = $("#about-section-id").outerHeight(),
    //     wH = $(window).height(),
    //     wS = $(this).scrollTop();
    //   if (wS > hT + hH - wH && hT > wS && wS + wH > hT + hH) {
    //     $(".about-removable-overlay").addClass("removable-overlay");
    //     $(".about-removable-overlay").addClass("removable-overlay");
    //     $(".about-removable-overlay").addClass("removable-overlay");
    //     $(".about-removable-overlay").addClass("removable-overlay");
    //   }
    // });
    
  },
  components: {
    Form
  }
};
</script>

<style lang="scss" scoped>
@for $i from 1 through 12 {
  .col-div-#{$i}::before {
    -webkit-animation: col-circle-animation 2s ease-in-out forwards;
    animation: col-circle-animation 2s ease-in-out forwards;
    animation-delay: 3s;
    -moz-animation-delay: 3s;
    -o-animation-delay: 3s;
  }

  .col-div-#{$i}::after {
    -webkit-animation: col-border-animation 2s ease-in-out forwards;
    animation: col-border-animation 2s ease-in-out forwards;
    animation-delay: 4s;
    -moz-animation-delay: 4s;
    -o-animation-delay: 4s;
  }

  .col-div-#{$i} {
    -webkit-animation: col-width-animation 0.5s ease-in-out forwards;
    animation: col-width-animation 0.5s ease-in-out forwards;
    animation-delay: 5.5s;
    -moz-animation-delay: 5.5s;
    -o-animation-delay: 5.5s;
  }

  .col-div-1::before,
  .col-div-1::after {
    display: none;
  }

  @-webkit-keyframes col-border-animation {
    0% {
      height: 0;
    }

    100% {
      height: 100%;
    }
  }

  @keyframes col-border-animation {
    0% {
      height: 0;
    }

    100% {
      height: 100%;
    }
  }

  @-webkit-keyframes col-circle-animation {
    0% {
      top: 0;
    }

    100% {
      top: 100%;
      opacity: 0;
    }
  }

  @keyframes col-circle-animation {
    0% {
      top: 0;
    }

    100% {
      top: 100%;
      opacity: 0;
    }
  }

  @-webkit-keyframes col-width-animation {
    0% {
      width: 100%;
    }

    100% {
      width: 0;
    }
  }

  @keyframes col-width-animation {
    0% {
      width: 100%;
    }

    100% {
      width: 0;
    }
  }
}
</style>
