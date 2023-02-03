<template>
  <div class="container text-white py-5">
    <div class="row p-5 bg-color">
      <div class="col col-12">
        <img src="../assets/images/what-is-gpt3/gradient-line.svg" alt="Line"/>
      </div>
      <div class="col col-4">
        <p class="fs-4 fw-bold">
          What is GPT-3
        </p>
      </div>
      <div class="col col-8">
        <p class="text-primary fw-500">
          We so opinion friends me message as delight. Whole front do of plate heard oh ought. His defective nor
          convinced residence own. Connection has put impossible own apartments boisterous. At jointure ladyship an
          insisted so humanity he. Friendly bachelor entrance to on by.
        </p>
      </div>
      <div class="col col-6 pt-5">
        <h2 class="text-gradient fw-bold">
          The possibilities are beyond<br/> your imagination
        </h2>
      </div>
      <div class="col col-6 d-flex flex-row align-items-center justify-content-end">
        <p class="p-custom-color fw-500">
          Explore The Library
        </p>
      </div>
      <div class="col col-4 pt-5" v-for="item in items">
        <img src="../assets/images/what-is-gpt3/gradient-line.svg" alt="Line"/>
        <p class="fs-4 fw-bold">
          {{ item.header }}
        </p>
        <p class="text-primary fw-500">
          {{ item.text }}
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "WhatIsGPT3",
  data() {
    return {
      items: [
        {
          header: 'Chatbots',
          text: 'We so opinion friends me message as delight. Whole front do of plate heard oh ought. '
        },
        {
          header: 'Knowledgebase',
          text: 'At jointure ladyship an insisted so humanity he. Friendly bachelor entrance to on by. As put impossible own apartments b'
        },
        {
          header: 'Education',
          text: 'At jointure ladyship an insisted so humanity he. Friendly bachelor entrance to on by. As put impossible own apartments b'
        },
      ]
    }
  }
}
</script>

<style scoped>
.fw-500 {
  font-weight: 500;
}

.fw-bold {
  font-weight: 800 !important;
}

h2 {
  font-size: 34px;
}

.p-custom-color {
  color: #FF8A71;
}

.bg-color {
  background-color: #042c54;
}
</style>
