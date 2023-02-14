<template>
  <div class="container py-5">
    <h1 class="text-gradient m-0 py-2 text-center text-lg-start">
      A lot is happening,<br/>
      We are blogging about it.
    </h1>
    <div class="row my-2">
      <div v-for="cardDetails in blogCards" class="col col-12 col-md-6 col-lg-4">
        <blog-card :card-details="cardDetails"/>
      </div>
    </div>
  </div>
</template>

<script>
import BlogCard from "@/components/BlogCard";
export default {
  name: "Blog",
  components: {BlogCard},
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
h1 {
  font-size: 62px;
  font-weight: 800;
}
</style>
