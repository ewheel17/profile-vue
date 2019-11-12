<template>
  <div class="home">
    <banner class="sectionComponent" />
    <about class="sectionComponent" />
    <skills class="sectionComponent" />
    <portfolio class="sectionComponent" />
    <Footer class="sectionComponent" />
  </div>
</template>

<script>
import Banner from "@/components/sections/Banner.vue";
import About from "@/components/sections/About.vue";
import Skills from "@/components/sections/Skills.vue";
import Portfolio from "@/components/sections/Portfolio.vue";
import Footer from "@/components/sections/Footer.vue";

export default {
  name: "home",
  components: {
    Banner,
    About,
    Skills,
    Portfolio,
    Footer
  }
};
</script>

<style lang="scss" scoped>
.home {
  // display: flex;
  // flex-flow: column;
  // height: 100%;
  // justify-content: space-between;
  // align-items: stretch;
}
</style>