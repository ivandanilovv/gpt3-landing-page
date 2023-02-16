<template>
  <h2 v-html="headerText" class="text-gradient"></h2>
</template>

<script>
export default {
  name: "HeaderTwo",
  props: {
    headerText: String,
  }
}
</script>

<style scoped>
h2 {
  font-size: 2.125rem;
  font-weight: 800;
}
</style>
