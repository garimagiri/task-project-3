<template>
  <div class="first-card">
    <div>
      <div class="d-flex justify-content-center">
        <img
          src="../images/first_img.jpg"
          width="350"
          height="325"
          class="mb-3"
          alt="firstimg"
        />
      </div>
      <h4 class="fw-bold" style="letter-spacing: 1px">
        Too many options to <span class="text-danger">choose</span> from?
      </h4>
      <p class="text-center mb-0">Relax.</p>
      <p>Let us help you find the right plan to protect your devices.</p>
      <div class="d-flex my-3 justify-content-center align-items-center">
        <button
          class="btn-tour me-4 fw-bold"
          type="submit"
          data-bs-toggle="modal"
          data-bs-target="#tourModal"
        >
          Take a tour
        </button>
        <button class="fw-bold close-btn" type="submit">close</button>
      </div>
    </div>
    <PageSecond/>
  </div>
</template>

<script>
import PageSecond from './PageSecond.vue'

export default {
  name: "PageOne",
  components:{
    PageSecond,
  }
};
</script>

