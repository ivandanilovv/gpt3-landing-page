<template>
  <div class="">
    <custom-navbar/>
    <div class="container text-white">
      <div class="row">
        <div class="col-12 col-xl-6 pt-5">
          <header-one header-text="Let’s Build Something amazing with GPT-3 OpenAI"
                      class="fw-bold text-center text-md-start"/>
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
  </div>
</template>

<script>
import HeaderOne from "@/components/base/HeaderOne";
import CustomNavbar from "@/components/CustomNavbar";

export default {
  name: "HeroSection",
  components: {
    HeaderOne,
    CustomNavbar
  }
}
</script>

<style scoped>
.p-custom-font {
  font-size: 1.25rem;
  font-weight: 400;
}

.button-custom-font {
  font-size: 1.25rem;
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

</style>
