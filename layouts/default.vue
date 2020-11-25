<template>
  <div>
    <Header />
    <div class="container">
      <nuxt />
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from "./Footer";
import Header from "./Header";

export default {
  components: {
    Footer,
    Header
  }
};
</script>
