<template>
  <div class="internal-page">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item">
          <nuxt-link to="/" class="no-line">الرئيسية</nuxt-link>
        </li>
        <li class="breadcrumb-item active" aria-current="page">الأخبار</li>
      </ol>
    </nav>

    <section class="blog-page blog-section">
      <div class="mid-padding">
        <div class="row">
          <div class="col-md-3" v-for="i in 8" :key="i">
            <article class="blog-box">
              <nuxt-link to="/single-blog" class="no-line">
                <div class="blog-img relative">
                  <img src="../static/images/2-blog.jpg" alt class="image-100" />

                  <div class="blog-caption-wrap small-padding absolute">
                    <div class="blog-caption-text-wrap small-padding absolute">
                      <div class="blog-insights">
                        <div class="blog-category">
                          <span class="blog-category-p white">العقارات</span>
                        </div>
                      </div>

                      <div class="home-blog-title">
                        <h3
                          class="home-blog-title-h3 white"
                        >رؤيتنا في الاتحاد للاستثمار والتطوير العقاري</h3>
                      </div>

                      <div class="home-blog-desc">
                        <p
                          class="home-blog-title-p white"
                        >أن نصبح رائدين في مجال الاستثمار والتطوير العقاري في الشرق الأوسط بأكمله وأن نكسب ونحافظ على رضا عملائنا من جميع أنحاء العالم</p>
                      </div>

                      <div class="home-blog-action">
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
                </div>
              </nuxt-link>
            </article>
          </div>
        </div>

        <div class="text-center">
          <div class="pagination">
            <a href="#">&laquo;</a>
            <a href="#" class="active disabled">1</a>
            <a href="#">2</a>
            <a href="#">3</a>
            <a href="#">4</a>
            <a href="#">5</a>
            <a href="#">6</a>
            <a href="#">&raquo;</a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>