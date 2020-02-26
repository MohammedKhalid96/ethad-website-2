<template>
  <div>
    <Nav />
    <nuxt />
    <Footer />
  </div>
</template>


<script>
import Nav from "~/components/Nav.vue";
import Footer from "~/components/Footer.vue";
import Form from "~/components/Form.vue";

export default {
  components: {
    Nav,
    Footer,
    Form
  }
};
</script>