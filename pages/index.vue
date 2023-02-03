<template>
  <div class="custom-bg-color">
    <hero-section/>
    <social-media-links/>
  </div>
</template>

<script>
import CustomNavbar from "~/components/CustomNavbar";
import HeroSection from "@/components/HeroSection";
import SocialMediaLinks from "@/components/SocialMediaLinks";

export default {
  name: 'IndexPage',
  components: {SocialMediaLinks, HeroSection, CustomNavbar}
}
</script>
