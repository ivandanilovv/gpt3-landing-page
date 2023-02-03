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
  </div>
</template>

<script>
import CustomNavbar from "~/components/CustomNavbar";
import HeroSection from "@/components/HeroSection";
import WhatIsGPT3 from "@/components/WhatIsGPT3";
import SocialMediaLinks from "@/components/SocialMediaLinks";
import TheFuture from "@/components/TheFuture";
import ThePossibilities from "@/components/ThePossibilities";
import RegisterToday from "@/components/RegisterToday";

export default {
  name: 'IndexPage',
  components: {RegisterToday, ThePossibilities, TheFuture, SocialMediaLinks, WhatIsGPT3, HeroSection, CustomNavbar}
}
</script>
