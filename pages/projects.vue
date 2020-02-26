<template>
  <div class="internal-page">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item">
          <nuxt-link to="/" class="no-line">الرئيسية</nuxt-link>
        </li>
        <li class="breadcrumb-item active" aria-current="page">سابقة الأعمال</li>
      </ol>
    </nav>

    <section class="projects-page projects-section">
      <div class="mid-padding">
        <div class="row">
          <div class="col-md-3">
            <div class="project-box small-project-box" v-for="i in 2" :key="i">
              <nuxt-link to="/">
                <div class="project-img relative">
                  <img src="../static/images/bg-new-4.jpg" alt class="image-100" />

                  <div class="project-overlay absolute">
                    <div class="project-caption-overlay small-padding absolute">
                      <p class="project-name">
                        <font-awesome-icon icon="building"></font-awesome-icon>كومبوند الجلاء العاصمة الادارية
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
                  <img src="../static/images/bg-new-4.jpg" alt class="image-100" />

                  <div class="project-overlay absolute">
                    <div class="project-caption-overlay small-padding absolute">
                      <p class="project-name">
                        <font-awesome-icon icon="building"></font-awesome-icon>كومبوند الجلاء العاصمة الادارية
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
                  <img src="../static/images/bg-new-4.jpg" alt class="image-100" />

                  <div class="project-overlay absolute">
                    <div class="project-caption-overlay small-padding absolute">
                      <p class="project-name">
                        <font-awesome-icon icon="building"></font-awesome-icon>كومبوند الجلاء العاصمة الادارية
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
  </div>
</template>