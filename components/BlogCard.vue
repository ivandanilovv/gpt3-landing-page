<template>
  <div class="bg-secondary p-2 rounded-4 mt-5">
    <div class="ratio ratio-41x18">
      <img :src="cardDetails.image" :alt="cardDetails.alt" class="rounded-pill">
    </div>
    <div class="bg-secondary text-white p-4">
      <p>
        {{ cardDetails.date }}
      </p>
      <h5 class="mb-5">
        {{ cardDetails.title }}
      </h5>
      <a :href="cardDetails.link" class="text-decoration-none text-white">
        Read Full Article
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlogCard",
  props: {
    cardDetails: Object
  }
}
</script>

<style scoped>

</style>
