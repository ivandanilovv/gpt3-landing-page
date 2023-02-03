<template>
  <div class="bg-custom-gradient">
    <hero-section/>
    <social-media-links/>
    <what-is-g-p-t3/>
  </div>
</template>

<script>
import CustomNavbar from "~/components/CustomNavbar";
import HeroSection from "@/components/HeroSection";
import WhatIsGPT3 from "@/components/WhatIsGPT3";
import SocialMediaLinks from "@/components/SocialMediaLinks";

export default {
  name: 'IndexPage',
  components: {SocialMediaLinks, WhatIsGPT3, HeroSection, CustomNavbar}
}
</script>
