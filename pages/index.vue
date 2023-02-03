<template>
  <div class="bg-custom-gradient">
    <hero-section/>
    <social-media-links/>
    <div class="bg-custom-gradient">
      <what-is-g-p-t3/>
      <the-future/>
    </div>
  </div>
</template>

<script>
import CustomNavbar from "~/components/CustomNavbar";
import HeroSection from "@/components/HeroSection";
import WhatIsGPT3 from "@/components/WhatIsGPT3";
import SocialMediaLinks from "@/components/SocialMediaLinks";
import TheFuture from "@/components/TheFuture";

export default {
  name: 'IndexPage',
  components: {TheFuture, SocialMediaLinks, WhatIsGPT3, HeroSection, CustomNavbar}
}
</script>
