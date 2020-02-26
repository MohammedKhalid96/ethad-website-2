<template>
  <b-navbar
    toggleable="lg"
    type="dark"
    class="navbar-expand-lg navbar-light bg-light slideInDown"
  >
    <nuxt-link to="/" class="navbar-brand">
      <img src="../static/images/logo.png" alt />
    </nuxt-link>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <nuxt-link to="/" class="nav-link">
          الرئيسية
          <span class="sr-only">(current)</span>
        </nuxt-link>
        <nuxt-link to="/services" class="nav-link lang">خدماتنا</nuxt-link>
        <nuxt-link to="/about" class="nav-link lang">رؤيتنا</nuxt-link>
        <nuxt-link to="/projects" class="nav-link lang">سابقة الأعمال</nuxt-link>
        <nuxt-link to="/blog" class="nav-link lang">الأخبار</nuxt-link>
        <nuxt-link to="/contact" class="nav-link lang">تواصل معنا</nuxt-link>
        <!-- <b-nav-item-dropdown text="Graphics" left>
          <b-dropdown-item to="/category">Logos</b-dropdown-item>
          <b-dropdown-item to="/category">Motion graphic</b-dropdown-item>
          <b-dropdown-item to="/category">Photography</b-dropdown-item>
        </b-nav-item-dropdown> -->
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="mr-auto">
        <b-nav-item class="pop-link" href="javaScript:void(0)">أرسل رسالة</b-nav-item>
        <b-nav-item href="tel:+201022088753">اتصل بنا</b-nav-item>
        <b-nav-item href="mailto:info@corddigital.com" class="other-lang">info@corddigital.com</b-nav-item>
        <nuxt-link to="/" class="nav-link other-lang other-lang-wrap">EN</nuxt-link>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>


<script>
import $ from "jquery";
export default {
  mounted: () => {}
};
</script>