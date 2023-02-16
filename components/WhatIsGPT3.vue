<template>
  <div class="container text-white py-0 py-sm-5">
    <div class="row p-5 bg-color">
      <div class="col col-12">
        <img src="../assets/images/what-is-gpt3/gradient-line.svg" alt="Line"/>
      </div>
      <div class="col col-12 col-md-4">
        <p class="fs-4 fw-bold">
          What is GPT-3
        </p>
      </div>
      <div class="col col-12 col-md-8">
        <p class="text-primary fw-500">
          We so opinion friends me message as delight. Whole front do of plate heard oh ought. His defective nor
          convinced residence own. Connection has put impossible own apartments boisterous. At jointure ladyship an
          insisted so humanity he. Friendly bachelor entrance to on by.
        </p>
      </div>
      <div class="col col-12 col-md-6 pt-5">
        <header-two header-text="The possibilities are beyond<br/> your imagination"
                    class="text-center text-md-start"/>
      </div>
      <div class="col col-12 col-md-6 d-flex flex-row align-items-center justify-content-center justify-content-md-end">
        <p class="p-custom-color fw-500">
          Explore The Library
        </p>
      </div>
      <div class="col col-lg-4 pt-5" v-for="item in items">
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
import HeaderTwo from "@/components/base/HeaderTwo";
export default {
  name: "WhatIsGPT3",
  components: {HeaderTwo},
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

.p-custom-color {
  color: #FF8A71;
}

.bg-color {
  /* ff 3.6+ */
  background:-moz-radial-gradient(circle at 30% -100%, #042c54 25%, rgba(4, 44, 84, 1) 85%, rgba(27, 120, 222, 1) 100%);

  /* safari 5.1+,chrome 10+ */
  background:-webkit-radial-gradient(circle at 30% -100%, #042c54 25%, rgba(4, 44, 84, 1) 85%, rgba(27, 120, 222, 1) 100%);

  /* opera 11.10+ */
  background:-o-radial-gradient(circle at 30% -100%, #042c54 25%, rgba(4, 44, 84, 1) 85%, rgba(27, 120, 222, 1) 100%);

  /* ie 10+ */
  background:-ms-radial-gradient(circle at 30% -100%, #042c54 25%, rgba(4, 44, 84, 1) 85%, rgba(27, 120, 222, 1) 100%);

  /* global 92%+ browsers support */
  background:radial-gradient(circle at 30% -100%, #042c54 25%, rgba(4, 44, 84, 1) 85%, rgba(27, 120, 222, 1) 100%);

  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
}
</style>
