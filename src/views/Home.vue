<template>
  <div id="home">
    <navbar/>
    <banner/>
    <about/>
    <skills/>
    <portfolio/>
    <contact/>
  </div>
</template>

<script>
import Navbar from "@/components/sections/Navbar.vue";
import Banner from "@/components/sections/Banner.vue";
import About from "@/components/sections/About.vue";
import Skills from "@/components/sections/Skills.vue";
import Portfolio from "@/components/sections/Portfolio.vue";
import Contact from "@/components/sections/Contact.vue";

export default {
  name: "home",
  components: {
    Banner,
    About,
    Skills,
    Portfolio,
    Contact,
    Navbar,
  }
};
</script>
