<template>
  <div class="internal-page">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item">
          <nuxt-link to="/" class="no-line">الرئيسية</nuxt-link>
        </li>
        <li class="breadcrumb-item active" aria-current="page">تواصل معنا</li>
      </ol>
    </nav>

    <section class="contact-page contact-section">
      <div class="mid-padding">
        <div class="row">
          <div class="col-md-4">
            <div class="contact-info">
              <li>
                <a class="no-line other-lang" href="tel:+0201004750956">
                  <font-awesome-icon icon="mobile-alt"></font-awesome-icon>01004750956
                </a>
              </li>

              <li>
                <a class="no-line other-lang" href="tel:+0201004750956">
                  <font-awesome-icon icon="mobile-alt"></font-awesome-icon>01004750956
                </a>
              </li>

              <li>
                <a class="other-lang no-line" href="mailto:info@ethad.com">
                  <font-awesome-icon icon="envelope"></font-awesome-icon>info@ethad.com
                </a>
              </li>

              <li>
                <a class="no-line" target="_blank" href>
                  <font-awesome-icon icon="map-marker-alt"></font-awesome-icon>ابراج رويال, السادس من اكتوبر, الجيزة
                </a>
              </li>
            </div>
          </div>

          <div class="col-md-8">
            <Form />
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
  mounted: () => {},
  components: {
    Form
  }
};
</script>