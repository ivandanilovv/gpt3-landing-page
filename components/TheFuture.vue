<template>
  <div class="container py-5 text-white">
    <div class="row">
      <div class="col col-12 col-lg-5">
        <header-two
          header-text="The Future is Now and You Just Need To Realize It. Step into Future Today & Make it Happen."
          class="pb-lg-3 text-center text-lg-start"/>
        <p class="p-custom-color py-5 text-center text-lg-start">
          Request Early Access to Get Started
        </p>
      </div>
      <div class="col col-12 col-lg-6 offset-lg-1">
        <div class="row" v-for="item in factsItems">
          <div class="col col-12">
            <img src="../assets/images/what-is-gpt3/gradient-line.svg" alt="Line"/>
          </div>
          <div class="col-5">
            <p class="fs-4 header-font-size">
              {{ item.header }}
            </p>
          </div>
          <div class="col col-7">
            <p class="text-primary fs-7">
              {{ item.text }}
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HeaderTwo from "@/components/base/HeaderTwo";
export default {
  name: "TheFuture",
  components: {HeaderTwo},
  data() {
    return {
      factsItems: [
        {
          header: 'Improving end distrusts instantly ',
          text: `From they fine john he give of rich he. They age and draw mrs like. Improving end distrusts may
            instantly was household applauded.`,
        },
        {
          header: 'Become the tended active',
          text: `Considered sympathize ten uncommonly occasional assistance sufficient not. Letter of on become he
            tended active enable to.`,
        },
        {
          header: 'Message or am nothing',
          text: `Led ask possible mistress relation elegance eat likewise debating. By message or am nothing
            amongst chiefly address.`,
        },
        {
          header: 'Really boy law county',
          text: `Really boy law county she unable her sister. Feet you off its like like six. Among sex are leave law
            built now. In built table in an rapid blush.`,
        },
      ]
    }
  }
}
</script>

<style scoped>
.header-font-size {
  font-size: 1.125rem;
  font-weight: 800;
}

.fs-7 {
  font-size: 0.875rem;
}

.p-custom-color {
  color: #FF8A71;
}
</style>
