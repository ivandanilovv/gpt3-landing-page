<template>
  <div class="d-none d-sm-flex flex-row align-items-center justify-content-center py-5">
    <a href="#" v-for="(image, i) in images">
<!--      <div class="ratio ratio-16x9">-->
        <img :src="image.src" :alt="image.alt" :class="{'ps-sm-3 ps-md-5' : i !== 0}">
<!--      </div>-->
    </a>
  </div>
</template>

<script>
export default {
  name: "SocialMediaLinks",
  data() {
    return {
      images: [
        {
          src: require('../assets/images/social-media-links/google.svg'),
          alt: 'Google logo',
        },
        {
          src: require('../assets/images/social-media-links/slack.svg'),
          alt: 'Slack logo',
        },
        {
          src: require('../assets/images/social-media-links/atlassian.svg'),
          alt: 'Atlassian logo',
        },
        {
          src: require('../assets/images/social-media-links/dropbox.svg'),
          alt: 'Dropbox logo',
        },
        {
          src: require('../assets/images/social-media-links/shopify.svg'),
          alt: 'Shopify logo',
        },
      ]
    }
  }
}
</script>

<style scoped>

</style>
