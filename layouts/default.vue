<template>
  <div>
    <FixedNav />
    <transition name="slide-fade">
      <nuxt />
    </transition>
    <Footer />
  </div>
</template>

<script>
import FixedNav from "~/components/FixedNav.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    FixedNav,
    Footer
  }
};
</script>
