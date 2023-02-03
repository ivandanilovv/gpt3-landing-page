<template>
  <div class="py-5 custom-bg-color text-white">
    <div class="container">
      <nav class="navbar navbar-expand-lg">
        <div class="container">
          <img src="../assets/images/custom-navbar/logo.svg" alt="Logo image" width="62.56" height="16.02"/>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                  data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                  aria-expanded="false"
                  aria-label="Toggle navigation">
            <span class="navbar-toggler-icon bg-orange p-3 rounded-3"></span>
          </button>
          <div class="collapse navbar-collapse flex-column justify-content-end flex-lg-row justify-content-lg-between"
               id="navbarSupportedContent">
            <ul class="navbar-nav text-center flex-column flex-lg-row justify-content-center align-items-center">
              <li class="nav-item" v-for="(item, i) in navbarItems">
                <a class="nav-link navbar-items-font ps-0 ps-lg-5 text-white" :class="{'active' : i === 0}"
                   aria-current="page"
                   :href=item.link>
                  {{ item.text }}
                </a>
              </li>
            </ul>
            <div class="d-flex flex-column flex-lg-row align-items-center">
              <a href="#" class="btn text-white navbar-items-font">
                Sign in
              </a>
              <a href="#" class="btn sign-up-button text-white navbar-items-font pt-3 ms-0 ms-lg-3">
                Sign up
              </a>
            </div>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "CustomNavbar",
  data() {
    return {
      navbarItems: [
        {
          link: '#',
          text: 'Home',
        },
        {
          link: '#',
          text: 'What is GPT?',
        },
        {
          link: '#',
          text: 'Open AI',
        },
        {
          link: '#',
          text: 'Case Studies',
        },
        {
          link: '#',
          text: 'Library',
        },
      ]
    }
  }
}
</script>

<style scoped>
.navbar-items-font {
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 25px;
}

.sign-up-button {
  background-color: #FF4820;
  width: 152px;
  height: 58px;
}

.bg-orange {
  background-color: #FF4820;
}

.navbar-nav {
  flex-direction: row;
}
</style>
