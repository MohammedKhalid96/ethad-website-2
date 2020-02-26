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
        <div class="row no-gutters">
          <div class="col-md-5">
            <div class="services-big-img">
              <img src="../static/images/2-blog.jpg" alt class="image-100" />
            </div>
          </div>

          <div class="col-md-7">
            <div class="services-caption mid-padding">
              <p class="small-caption white">معايير عالمي في مجال المقاولات الصناعية</p>
              <h3 class="services-title-h3 orange">الحل الأفضل للجميع</h3>
              <p
                class="services-caption white"
              >مشاريع سكنية وإدارية وتجارية ورياضية وترفيهية يقدمها لك الاتحاد بتصاميم إبداعية ومبتكرة غير مسبوقة تجربة مختلفة واستثنائية في الاتحاد للاستثمار والتطوير العقاري مع أحدث الأساليب المتبعة في التخطيط والتصميم والتنفيذ والإدارة لتحصل على ما تريد بأفضل جودة ممكنة</p>

              <div class="services-slider">
                <carousel
                  :perPageCustom="[[320, 1], [768, 2], [1024, 2]]"
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
                              <img src="../static/images/service-1.png" alt class="image-100" />
                            </div>
                          </div>

                          <div class="col-6 d-flex align-items-center">
                            <div class="service-caption small-padding">
                              <h5 class="service-name white">أنظمة دفع مختلفة</h5>
                              <div class="action-link relative">
                                <span class="f-width-link link">
                                  <span class="link-arrow">
                                    <font-awesome-icon
                                      icon="plus"
                                    ></font-awesome-icon>
                                  </span>
                                  المزيد
                                </span>
                                <div class="frame top-frame"></div>
                                <div class="frame bottom-frame"></div>
                                <div class="frame left-frame"></div>
                                <div class="frame right-frame"></div>
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
  </div>
</template>