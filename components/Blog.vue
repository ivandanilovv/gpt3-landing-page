<template>
  <div class="container py-5">
    <header-one header-text="A lot is happening,<br/> We are blogging about it."
                class="m-0 py-2 text-center text-lg-start"/>
    <div class="row my-2">
      <div v-for="cardDetails in blogCards" class="col col-12 col-md-6 col-lg-4">
        <blog-card :card-details="cardDetails"/>
      </div>
    </div>
  </div>
</template>

<script>
import BlogCard from "@/components/BlogCard";
import HeaderOne from "@/components/base/HeaderOne";

export default {
  name: "Blog",
  components: {
    BlogCard,
    HeaderOne
  },
  data() {
    return {
      blogCards: [
        {
          image: require('../assets/images/blog-cards/image2.svg'),
          alt: 'Image  1',
          date: 'Feb 14, 2023',
          title: `GPT-3 and Open  AI is the future. Let us explore how it is?`,
          link: '#',
        },
        {
          image: require('../assets/images/blog-cards/image3.svg'),
          alt: 'Image  1',
          date: 'Feb 14, 2023',
          title: `GPT-3 and Open  AI is the future. Let us explore how it is?`,
          link: '#',
        },
        {
          image: require('../assets/images/blog-cards/image4.svg'),
          alt: 'Image  1',
          date: 'Feb 14, 2023',
          title: `GPT-3 and Open  AI is the future. Let us explore how it is?`,
          link: '#',
        },
      ]
    }
  }
}
</script>

<style scoped>

</style>
