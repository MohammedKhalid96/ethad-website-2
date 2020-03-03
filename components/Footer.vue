<template>
  <footer>
    <div class="mid-padding">
      <div class="row">
        <div class="col-md-3">
          <div class="footer-about">
            <div class="footer-logo">
              <img src="../static/images/logo.png" alt />
            </div>

            <div class="footer-about-caption">
              <p class="footer-about-caption-p">
                مشاريع سكنية وإدارية وتجارية ورياضية وترفيهية يقدمها لك الاتحاد
                بتصاميم إبداعية ومبتكرة غير مسبوقة
              </p>
            </div>

            <div class="action-link relative">
              <nuxt-link to="/" class="link no-line">
                <span class="link-arrow">
                  <font-awesome-icon icon="plus"></font-awesome-icon>
                </span>
                المزيد
              </nuxt-link>
              
              <nuxt-link to="/" class="link no-line">
                <span class="link-arrow">
                  <font-awesome-icon icon="paper-plane"></font-awesome-icon>
                </span>
                تواصل معنا
              </nuxt-link>
            </div>
          </div>
        </div>

        <div class="col-md-3">
          <div class="footer-posts">
            <div class="footer-title">
              <h3 class="footer-title-h3">احدث المقالات</h3>
            </div>

            <li>
              <nuxt-link to="/" class="no-line"
                >يهتم الاتحاد بأنماط الحياة العصرية الراقية لذا صمم لك مجموعات
                عقارية بمختلف الديكورات</nuxt-link
              >
            </li>

            <li>
              <nuxt-link to="/" class="no-line"
                >يهتم الاتحاد بأنماط الحياة العصرية الراقية لذا صمم لك مجموعات
                عقارية بمختلف الديكورات</nuxt-link
              >
            </li>

            <li>
              <nuxt-link to="/" class="no-line"
                >يهتم الاتحاد بأنماط الحياة العصرية الراقية لذا صمم لك مجموعات
                عقارية بمختلف الديكورات</nuxt-link
              >
            </li>
          </div>
        </div>

        <div class="col-md-3">
          <div class="footer-contact">
            <div class="footer-title">
              <h3 class="footer-title-h3">تواصل معنا</h3>
            </div>

            <li>
              <a
                href="tel:+0201004750956"
                target="_blank"
                class="other-lang no-line"
              >
                <font-awesome-icon icon="mobile-alt"></font-awesome-icon
                >01004750956
              </a>
            </li>

            <li>
              <a
                href="tel:+0201004750956"
                target="_blank"
                class="other-lang no-line"
              >
                <font-awesome-icon icon="mobile-alt"></font-awesome-icon
                >01004750956
              </a>
            </li>

            <li>
              <a href="#" class="other-lang no-line">
                <font-awesome-icon icon="envelope"></font-awesome-icon
                >info@ethad.com
              </a>
            </li>

            <li>
              <a href="#" target="_blank" class="no-line">
                <font-awesome-icon icon="map-marker-alt"></font-awesome-icon
                >ابراج رويال, السادس من اكتوبر, الجيزة
              </a>
            </li>
          </div>
        </div>

        <div class="col-md-3">
          <div class="footer-subscribe">
            <div class="footer-title">
              <h3 class="footer-title-h3">تابعنا</h3>
            </div>
            <form action="#" method="post">
              <div class="form-group">
                <input
                  type="email"
                  class="form-control"
                  name="email"
                  id="form-email"
                  aria-describedby="email"
                  placeholder="برجاء ادخال البريد الالكتروني"
                  required
                />
              </div>

              <div class="form-group action-btn-wrap">
                <button type="submit" class="btn action-btn link">
                  <span class="link-arrow">
                    <font-awesome-icon icon="paper-plane"></font-awesome-icon>
                  </span>
                  أرسال
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  background: linear-gradient(to top, #0c1f33, #0c1f3369, transparent),
    url("../static/images/footer-pattern.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: contain;

  .footer-title-h3 {
    color: #c7712c;
    margin-bottom: 1em;
    margin-top: 1.5em;
  }

  li {
    margin-bottom: 1.5em;
  }

  a {
    color: #fff;
  }

  svg {
    width: 0.8em;
    margin-left: 0.5em;
    color: #c7712c;
  }

  .action-link {
    a {
      color: #0c1f33;
    }
  }

  .footer-about {
    img {
      width: 130px;
    }

    .footer-about-caption-p {
      color: #fff;
    }
  }

  .footer-subscribe {
  }
}
</style>
