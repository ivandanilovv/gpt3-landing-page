<template>
  <div class="bg-secondary pt-5">
    <div class="container">
      <div class="d-flex flex-column justify-content-center align-items-center text-center py-5">
        <h1 class="text-gradient mt-5 mb-0 pb-5">
          Do you want to step in to the<br/> future before others
        </h1>
        <button class="btn btn-outline-light rounded-0 fs-4 my-5 p-3">
          Request Early Access
        </button>
      </div>
      <div class="row py-5 d-flex flex-row justify-content-evenly">
        <div class="col-md-3 d-flex flex-row align-items-start justify-content-center">
          <img src="../assets/images/custom-footer/logo-footer.svg" alt="Logo" class="d-none d-md-block"/>
        </div>
        <div v-for="(item, i) in footerItems" class="col col-4 col-md-3 col-lg-2 d-flex flex-column align-items-start"
          :class="{'offset-lg-2' : i === 0}">
          <h5 class="text-white fw-bold">
            {{ item.header }}
          </h5>
          <ul class="m-0 p-0">
            <li v-for="link in item.links" class="py-2 py-lg-3">
              <a :href="link.src" class="text-decoration-none text-white">
                {{ link.text }}
              </a>
            </li>
          </ul>
          <ul class="m-0 p-0 text-white">
            <li v-for="paragraph in item.paragraphs" class="py-2 py-lg-3">
              <p class="m-0">
                {{paragraph}}
              </p>
            </li>
          </ul>
        </div>
      </div>
      <p class="text-white text-center m-0 pb-3">
        &copy;2023 Ivan Danilov. All rights reserved.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "CustomFooter",
  data() {
    return {
      footerItems: [
        {
          header: 'Links',
          links: [
            {
              src: '#',
              text: 'Overons',
            },
            {
              src: '#',
              text: 'Social Media',
            },
            {
              src: '#',
              text: 'Counters',
            },
          ]
        },
        {
          header: 'Company',
          links: [
            {
              src: '#',
              text: 'Terms & Conditions',
            },
            {
              src: '#',
              text: 'Privacy Policy',
            },
            {
              src: '#',
              text: 'Contact',
            },
          ]
        },
        {
          header: 'Get in touch',
          links: [],
          paragraphs: [
            'Crechterwoord K12 182 DK Alknjkcb', '085-132567', 'info@payme.net'
          ]
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
ul {
  list-style: none;
}
</style>
