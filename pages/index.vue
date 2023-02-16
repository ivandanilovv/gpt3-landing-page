<template>
  <div class="bg-custom-gradient">
    <hero-section/>
    <social-media-links/>
    <div class="bg-custom-gradient">
      <what-is-g-p-t3/>
      <the-future/>
    </div>
    <the-possibilities/>
    <register-today/>
    <blog/>
    <custom-footer/>
  </div>
</template>

<script>
import Blog from "@/components/Blog";
import TheFuture from "@/components/TheFuture";
import WhatIsGPT3 from "@/components/WhatIsGPT3";
import HeroSection from "@/components/HeroSection";
import CustomFooter from "@/components/CustomFooter";
import CustomNavbar from "~/components/CustomNavbar";
import RegisterToday from "@/components/RegisterToday";
import SocialMediaLinks from "@/components/SocialMediaLinks";
import ThePossibilities from "@/components/ThePossibilities";

export default {
  name: 'IndexPage',
  components: {
    Blog,
    TheFuture,
    WhatIsGPT3,
    HeroSection,
    CustomFooter,
    CustomNavbar,
    RegisterToday,
    SocialMediaLinks,
    ThePossibilities,
  }
}
</script>
