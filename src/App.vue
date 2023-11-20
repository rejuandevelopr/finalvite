<template>
  <div id="app">
    <HeroSection />
    <FeaturesSection />
    <CTASection />
  </div>
</template>

<script>
import HeroSection from "@/components/HeroSection.vue";
import FeaturesSection from "@/components/FeaturesSection.vue";
import CTASection from "@/components/CTASection.vue";

export default {
  components: {
    HeroSection,
    FeaturesSection,
    CTASection,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
