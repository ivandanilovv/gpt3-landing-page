<template>
  <div class="container py-4">
    <div class="row py-5 bg-purple-gradient rounded-4">
      <div class="col col-12 col-sm-9 d-flex flex-column justify-content-center p-0 px-2 ps-md-5">
        <p class="fw-500 text-center text-sm-start">
          Request Early Access to Get Started
        </p>
        <p class="fs-4 fw-800 text-center text-sm-start">
          Register today & start exploring the endless possiblities.
        </p>
      </div>
      <div class="col col-12 col-sm-3 d-flex flex-column justify-content-center align-items-end">
        <button class="btn btn-dark p-0 py-2 rounded-5 fs-6 me-lg-5 custom-button-width">
          Get Started
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RegisterToday"
}
</script>

<style scoped>
.fs-6 {
  font-size: 18px !important;
}

.btn-dark {
  background-color: black;
}

.bg-purple-gradient {

  /* ff 3.6+ */
  background:-moz-linear-gradient(90deg, rgba(174, 103, 250, 1) 0%, rgba(242, 150, 108, 1) 100%);

  /* safari 5.1+,chrome 10+ */
  background:-webkit-linear-gradient(90deg, rgba(174, 103, 250, 1) 0%, rgba(242, 150, 108, 1) 100%);

  /* opera 11.10+ */
  background:-o-linear-gradient(90deg, rgba(174, 103, 250, 1) 0%, rgba(242, 150, 108, 1) 100%);

  /* ie 6-9 */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#F2966C', endColorstr='#AE67FA', GradientType=0 );

  /* ie 10+ */
  background:-ms-linear-gradient(90deg, rgba(174, 103, 250, 1) 0%, rgba(242, 150, 108, 1) 100%);

  /* global 94%+ browsers support */
  background:linear-gradient(90deg, rgba(174, 103, 250, 1) 0%, rgba(242, 150, 108, 1) 100%);

}

.fw-800 {
  font-weight: 800;
}

.fw-500 {
  font-weight: 500;
}

@media (max-width: 992px) {
  .custom-button-width {
    width: 100% !important;
  }
}

@media (min-width: 992px) {
  .custom-button-width {
    width: 75% !important;
  }
}

</style>
