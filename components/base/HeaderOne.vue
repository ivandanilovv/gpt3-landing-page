<template>
  <h1 class="text-gradient" v-html="headerText"></h1>
</template>

<script>
export default {
  name: "HeaderOne",
  props: {
    headerText: String,
  }
}
</script>

<style scoped>
h1 {
  font-size: 3.88rem;
  font-weight: 800;
}
</style>
