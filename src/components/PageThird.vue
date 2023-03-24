<template>
  <div
    class="modal fade"
    id="tourplanModal"
    tabindex="-1"
    aria-labelledby="exampleModalLabel2"
    aria-hidden="true"
  >
    <div class="modal-dialog modal-fullscreen">
      <div class="modal-content" style="border-radius: 40px">
        <div class="modal-header border-0">
          <h6 class="modal-title" id="exampleModalLabel2">
            <span class="rounded-circle bg-secondary text-white me-3">1</span
            ><span class="rounded-circle bg-warning text-light">2</span>
          </h6>
        </div>
        <div class="modal-body">
          <h1 class="text-center mb-3">Our Plans</h1>
          <div class="row" style="margin: 0 5rem 3rem 5rem">
            <div class="col-sm-4">
              <!--card one begin-->
              <div class="box-item">
                <div class="flip-box">
                  <div class="flip-box-front">
                    <div class="inner">
                        <span class="arrow-text"> >> </span> 
                      <h4 class="text-center mb-2">Multi-User</h4>
                      <div class="text-center">
                        <span class="fw-bolder fs-1 me-1">₹699*</span>
                        <span class="fs-9 text-secondary">/ year</span>
                      </div>
                      <div class="fs-9 fw-bold mb-4 text-center fs-5 fw-bold">
                        <span
                          class="text-decoration-line-through text-secondary me-2"
                          >₹2,199</span
                        ><span class="text-warning">(68% OFF)</span>
                      </div>
                      <div>
                        <div class="mb-2">
                          <img
                            src="../images/tick_mark.svg"
                            class="me-1"
                            width="25px"
                          /><span>3 Devices- 1 Year</span>
                        </div>
                        <div class="mb-2">
                          <img
                            src="../images/tick_mark.svg"
                            class="me-1"
                            width="25px"
                          /><span>Web Protection</span>
                        </div>
                        <div class="mb-2">
                          <img
                            src="../images/tick_mark.svg"
                            class="me-1"
                            width="25px"
                          /><span>Password Manager</span>
                        </div>
                        <div class="mb-2">
                          <img
                            src="../images/tick_mark.svg"
                            class="me-1"
                            width="25px"
                          /><span>Quick Clean & Shredder</span>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="flip-box-back">
                    <div class="inner">
                      <h4 class="text-center my-4">Multi-User</h4>
                      <div class="text-center mb-4">
                        <img src="../images/third_img.png" width="30%" />
                      </div>
                      <div class="d-flex justify-content-center">
                        <button class="buy-now-btn fw-bold" type="submit">
                          Buy Now
                        </button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <!--card one end-->
            </div>

            <div class="col-sm-4">
                <!--second card begin-->
                <div class="box-item">
                <div class="flip-box">
                  <div class="flip-box-front flip-box-mid">
                    <div class="inner pt-0">
                        <span class="arrow-text" style="top: -8px;"> >> </span>
                        <h4 class="text-center mb-2">Individual</h4>
                  <div class="text-center">
                    <span class="fw-bolder fs-1 me-1">₹299*</span>
                    <span class="fs-9">/ year</span>
                  </div>
                  <div class="fs-9 fw-bold mb-4 text-center fs-5 fw-bold">
                    <span class="text-decoration-line-through me-2">₹2,199</span
                    ><span class="text-warning">(77% OFF)</span>
                  </div>
                      <div>
                        <div class="mb-2">
                          <img
                            src="../images/tick_mark.svg"
                            class="me-1"
                            width="25px"
                          /><span>3 Devices- 1 Year</span>
                        </div>
                        <div class="mb-2">
                          <img
                            src="../images/tick_mark.svg"
                            class="me-1"
                            width="25px"
                          /><span>Web Protection</span>
                        </div>
                        <div class="mb-2">
                          <img
                            src="../images/tick_mark.svg"
                            class="me-1"
                            width="25px"
                          /><span>Password Manager</span>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="flip-box-back flip-box-mid">
                    <div class="inner">
                      <h4 class="text-center my-4">Individual</h4>
                      <div class="text-center mb-4">
                        <img src="../images/third_img.png" width="30%" />
                      </div>
                      <div class="d-flex justify-content-center">
                        <button class="buy-now-btn fw-bold mid-btn" type="submit">
                          Buy Now
                        </button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <!--second card end-->
            </div>

            <div class="col-sm-4">
              <!--third card begin-->
              <div class="box-item">
                <div class="flip-box">
                  <div class="flip-box-front">
                    <div class="inner">
                        <span class="arrow-text" style="top: 30px;"> >> </span>
                      <h4 class="text-center my-2 ">Family</h4>
                      <div class="text-center">
                        <span class="fw-bolder fs-1 me-1">₹1,999*</span>
                        <span class="fs-9 text-secondary">/ year</span>
                      </div>
                      <div class="fs-9 fw-bold mb-4 text-center fs-5 fw-bold">
                        <span
                          class="text-decoration-line-through text-secondary me-2"
                          >₹4,199</span
                        ><span class="text-warning">(60% OFF)</span>
                      </div>
                      <div>
                        
                        <div class="mb-2">
                      <img
                        src="../images/tick_mark.svg"
                        class="me-1"
                        width="25px"
                      /><span>Unlimited Devices- 1 Year</span>
                    </div>
                    <div class="mb-2">
                      <img
                        src="../images/tick_mark.svg"
                        class="me-1"
                        width="25px"
                      /><span>Web Protection</span>
                    </div>
                    <div class="mb-2">
                      <img
                        src="../images/tick_mark.svg"
                        class="me-1"
                        width="25px"
                      /><span>Password Manager</span>
                    </div>
                    <div class="mb-2">
                      <img
                        src="../images/tick_mark.svg"
                        class="me-1"
                        width="25px"
                      /><span>Identity Monitoring</span>
                    </div>
                    <div class="mb-2">
                      <img
                        src="../images/tick_mark.svg"
                        class="me-1"
                        width="25px"
                      /><span>Quick Clean & Shredder</span>
                    </div>
                      </div>
                    </div>
                  </div>
                  <div class="flip-box-back">
                    <div class="inner">
                      <h4 class="text-center my-4">Family</h4>
                      <div class="text-center mb-4">
                        <img src="../images/third_img.png" width="30%" />
                      </div>
                      <div class="d-flex justify-content-center">
                        <button class="buy-now-btn fw-bold" type="submit">
                          Buy Now
                        </button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <!--third card end-->
            </div>
          </div>
          <h4 class="text-center mb-5">
            and many more benefits with McAfee Livesafe Protection.
          </h4>
          <div class="d-flex justify-content-center">
            <button
              class="continue-btn me-4 fw-bold"
              type="submit"
              data-bs-toggle="modal"
              data-bs-target="#tourModal"
            >
              Previous
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
    <PageSecond />
  </div>
</template>

<script>
import PageSecond from "./PageSecond.vue";
export default {
  name: "PageThird",
  components: {
    PageSecond,
  },
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
