<template>
  <div
    class="modal fade"
    id="tourModal"
    tabindex="-1"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog modal-fullscreen">
      <div class="modal-content" style="border-radius: 40px">
        <div class="modal-header border-0">
          <h6 class="modal-title" id="exampleModalLabel">
            <span class="rounded-circle bg-warning text-light me-3">1</span
            ><span class="rounded-circle bg-secondary text-light">2</span>
          </h6>
        </div>
        <div class="modal-body">
          <h1 class="text-center mb-3">Select Your Operating System</h1>
          <div class="row" style="margin: 0 8rem 3rem 8rem">
            <div class="col-sm-4 gx-5">
              <div class="card border-0 os-cards mx-3">
                <div class="card-body p-5 mb-3">
                  <div class="d-flex justify-content-center mb-4">
                    <img src="../images/windows.png" width="150" />
                  </div>
                  <div class="text-center">windows</div>
                </div>
              </div>
            </div>
            <div class="col-sm-4 gx-5">
              <div class="card border-0 os-cards mx-3">
                <div class="card-body p-5 mb-3">
                  <div class="d-flex justify-content-center mb-4">
                    <img src="../images/apple_logo.png" width="150" />
                  </div>
                  <div class="text-center">Apple</div>
                </div>
              </div>
            </div>
            <div class="col-sm-4 gx-5">
              <div class="card border-0 os-cards mx-3">
                <div class="card-body p-5 mb-3">
                  <div class="d-flex justify-content-center mb-4">
                    <img src="../images/android.png" width="150" />
                  </div>
                  <div class="text-center">Android</div>
                </div>
              </div>
            </div>
          </div>
          <div class="d-flex justify-content-center">
            <button
              class="continue-btn me-4 fw-bold"
              type="submit"
              data-bs-toggle="modal"
              data-bs-target="#tourplanModal"
            >
              Continue
            </button>
          </div>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn fw-bold" data-bs-dismiss="modal">
            Close
          </button>
        </div>
      </div>
    </div>
    <PageThird/>
  </div>
</template>

<script>
import PageThird from './PageThird.vue'
export default {
  name: "PageSecond",
  components:{
    PageThird
  }
};
</script>
<style scoped>
.modal {
  top: -5px !important;
}
.modal-fullscreen {
  width: 97vw;
  max-width: none;
  height: 95%;
  margin: 0 1rem;
}
</style>
