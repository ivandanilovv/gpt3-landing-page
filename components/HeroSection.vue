<template>
  <div class="bg-custom-gradient">
    <custom-navbar/>
    <div class="container text-white">
      <div class="row">
        <div class="col-12 col-xl-6 pt-5">
          <h1 class="h1-custom-font-size text-gradient text-center text-md-start">
            Let’s Build Something
            amazing with GPT-3
            OpenAI
          </h1>
          <p class="p-custom-font text-primary pt-5 text-center text-md-start">
            Yet bed any for travelling assistance indulgence unpleasing.<br/>
            Not thoughts all exercise blessing. Indulgence way<br/>
            everything joy alteration boisterous the attachment. Party<br/>
            we years to order allow asked of.
          </p>
          <div class="d-flex flex-row">
            <input type="text" placeholder="Your Email Address" name="email"
                   class="w-65 ps-3 py-2 border-0 rounded-start input-bg-color p-custom-font"/>
            <a href="#" class="btn bg-orange w-34 button-custom-font border-0 rounded-0 rounded-end button-hover">
              Get Started
            </a>
          </div>
          <div class="d-flex flex-row align-items-center justify-content-center justify-content-md-start pt-3">
            <img src="../assets/images/hero-section/people.svg" alt="People" width="182" height="38"/>
            <p class="p-0 m-0 fs-7">
              1,600 people requested access a visit in last 24 hours
            </p>
          </div>
        </div>
        <div class="col-12 col-xl-6">
          <div class="ratio ratio-223x234">
            <img src="../assets/images/hero-section/head.svg" alt="Head"/>
          </div>
        </div>
      </div>
    </div>
    <social-media-links/>
  </div>
</template>

<script>
import CustomNavbar from "@/components/CustomNavbar";
import SocialMediaLinks from "@/components/SocialMediaLinks";

export default {
  name: "HeroSection",
  components: {SocialMediaLinks, CustomNavbar}
}
</script>

<style scoped>
.h1-custom-font-size {
  font-size: 3.75rem;
}

.p-custom-font {
  font-size: 20px;
  font-weight: 400;
}

.button-custom-font {
  font-size: 20px;
  font-weight: 700;
  color: white;
}

.input-bg-color {
  background-color: #052D56;
}

.w-34 {
  width: 34% !important;
}

.w-65 {
  width: 65% !important;
}

.fs-7 {
  font-size: 0.75rem;
}

.button-hover:hover {
  background-color: #cc300e;
}

.bg-custom-gradient {

  /* ff 3.6+ */
  background: -moz-radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 100%);

  /* safari 5.1+,chrome 10+ */
  background: -webkit-radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 100%);

  /* opera 11.10+ */
  background: -o-radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 100%);

  /* ie 10+ */
  background: -ms-radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 100%);

  /* global 92%+ browsers support */
  background: radial-gradient(circle at 3% 25%, rgba(0, 40, 83, 1) 0%, rgba(4, 12, 24, 1) 100%);

}

</style>
