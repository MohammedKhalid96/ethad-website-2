<template>
  <div class="internal-page">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item">
          <nuxt-link to="/" class="no-line">الرئيسية</nuxt-link>
        </li>
        <li class="breadcrumb-item active" aria-current="page">خدماتنا</li>
      </ol>
    </nav>

    <section class="services-page services-section">
      <div class="top-bottom-padding">
        <div class="title-circle">
          <h3 class="section-title-h3">
            الخدمات
          </h3>
        </div>
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
              <p class="services-caption-p white">
                مشاريع سكنية وإدارية وتجارية ورياضية وترفيهية يقدمها لك الاتحاد
                بتصاميم إبداعية ومبتكرة غير مسبوقة تجربة مختلفة واستثنائية في
                الاتحاد للاستثمار والتطوير العقاري مع أحدث الأساليب المتبعة في
                التخطيط والتصميم والتنفيذ والإدارة لتحصل على ما تريد بأفضل جودة
                ممكنة
              </p>

              <div class="services-slider text-center">
                <carousel
                  :perPageCustom="[
                    [320, 1],
                    [768, 1],
                    [1024, 4]
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
                  <slide>
                    <div class="service-box">
                      <nuxt-link to="/" class="no-line">
                        <div class="service-img">
                          <img
                            src="../static/images/new/الأستثمار-والتطوير-العقاري.png"
                            alt
                          />
                        </div>

                        <div class="service-caption">
                          <h5 class="service-name white">
                            الأستثمار والتطوير العقاري
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
                      </nuxt-link>
                    </div>
                  </slide>

                  <slide>
                    <div class="service-box">
                      <nuxt-link to="/" class="no-line">
                        <div class="service-img">
                          <img
                            src="../static/images/new/التشييد-والبناء.png"
                            alt
                          />
                        </div>

                        <div class="service-caption">
                          <h5 class="service-name white">
                            التشييد والبناء
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
                      </nuxt-link>
                    </div>
                  </slide>

                  <slide>
                    <div class="service-box">
                      <nuxt-link to="/" class="no-line">
                        <div class="service-img">
                          <img
                            src="../static/images/new/مجموعات-عقارية-بمختلف-الديكورات.png"
                            alt
                            class="image-100"
                          />
                        </div>

                        <div class="service-caption">
                          <h5 class="service-name white">
                            مجموعات عقارية بمختلف الديكورات
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
                      </nuxt-link>
                    </div>
                  </slide>

                  <slide>
                    <div class="service-box">
                      <nuxt-link to="/" class="no-line">
                        <div class="service-img">
                          <img
                            src="../static/images/new/انظمة-دفع-مختلفة-.png"
                            alt
                            class="image-100"
                          />
                        </div>

                        <div class="service-caption">
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
                      </nuxt-link>
                    </div>
                  </slide>

                  <slide>
                    <div class="service-box">
                      <nuxt-link to="/" class="no-line">
                        <div class="service-img">
                          <img
                            src="../static/images/new/خدمات-ما-بعد-البيع.png"
                            alt
                            class="image-100"
                          />
                        </div>

                        <div class="service-caption">
                          <h5 class="service-name white">
                            خدمات ما بعد البيع
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
                      </nuxt-link>
                    </div>
                  </slide>

                  <slide>
                    <div class="service-box">
                      <nuxt-link to="/" class="no-line">
                        <div class="service-img">
                          <img
                            src="../static/images/new/مساحات-مختلفة-من-الوحدات-السكنية.png"
                            alt
                            class="image-100"
                          />
                        </div>

                        <div class="service-caption">
                          <h5 class="service-name white">
                            وحدات سكنية بمساحات مختلفة
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
                      </nuxt-link>
                    </div>
                  </slide>

                  <slide>
                    <div class="service-box">
                      <nuxt-link to="/" class="no-line">
                        <div class="service-img">
                          <img
                            src="../static/images/new/مساحات-مختلفة-من-الوحدات-السكنية.png"
                            alt
                            class="image-100"
                          />
                        </div>

                        <div class="service-caption">
                          <h5 class="service-name white">
                            وحدات سكنية بمساحات مختلفة
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
  </div>
</template>
