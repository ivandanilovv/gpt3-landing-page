<template>
  <div class="custom-bg-color">
    <hero-section/>
    <what-is-g-p-t3/>
  </div>
</template>

<script>
import CustomNavbar from "~/components/CustomNavbar";
import HeroSection from "@/components/HeroSection";
import WhatIsGPT3 from "@/components/WhatIsGPT3";

export default {
  name: 'IndexPage',
  components: {WhatIsGPT3, HeroSection, CustomNavbar}
}
</script>
