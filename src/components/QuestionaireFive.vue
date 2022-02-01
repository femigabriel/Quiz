<template>
  <form class="form">
    <div class="Step1">
      <div class="row">
        <div class="test-questions comp">
          <div id="question1">
            <div class="question">
              <div class="form-title">
                <p>
                  Enter your <strong>name</strong> and
                  <strong>email address</strong> to see your results!
                </p>
              </div>
              <div class="divider"></div>
              <div class="step div">
                <div class="item">
                  <div class="div">
                    <input
                      name="name"
                      autofocus=""
                      type="text"
                      placeholder="Name"
                      class="name input"
                    />
                  </div>
                </div>
              </div>
              <div class="step div">
                <div class="item">
                  <div class="div">
                    <input
                      class="email input"
                      name="email"
                      placeholder="Email"
                      type="email"
                    />
                  </div>
                  <p class="smallTextEU"></p>
                </div>
              </div>
              <div class="div">
                <button
                  type="button"
                  class="continue button continue_e9QCT submitBtn"
                >
                  <div class="lds-ellipsis" style="display: none">
                    <div></div>
                    <div></div>
                    <div></div>
                    <div></div>
                  </div>
                  <span class="span text"
                    >See My Results
                    <i class="fa fa-angle-right" aria-hidden="true"></i
                  ></span>
                </button>
              </div>
            </div>
            <div class="Step6" style="display: none">
              <h2 class="h2">Where should your free reading be sent to?</h2>
              <div class="seperator div seperator_2B5q5"></div>
              <div class="step div">
                <div class="item">
                  <div class="div">
                    <input
                      class="email input"
                      name="email"
                      placeholder="Enter Your Email..."
                      type="email"
                    />
                  </div>
                  <p class="smallTextEU"></p>
                </div>
              </div>
              <div class="div">
                <button
                  type="button"
                  class="continue button continue_e9QCT submitBtn"
                >
                  <div class="loader" style="display: none"></div>
                  <span class="span text"
                    >Start My Reading
                    <i class="fa fa-angle-right" aria-hidden="true"></i
                  ></span>
                </button>
              </div>
            </div>
            <div class="errorMsg"></div>
          </div>
        </div>
      </div>
    </div>

     <div class="div">
      <button @click="saveData" type="button" class="continue">
        <span class="span"
          >NEXT <i class="fa fa-angle-right" aria-hidden="true"></i
        ></span>
         </button>
            <br>
    </div>
     <div class="previous">
        <button @click="previous" type="button" class="continue">
        <span class="span"
          >PREVIOUS <i class="fa fa-angle-right" aria-hidden="true"></i
        ></span>
      </button>
    </div>
  </form>
</template>
<script>
export default {
  emits: [],
  methods: {
    saveData() {
      this.$emit("gotoNext");
    },
     previous() {
      this.$emit("gotoPrevious");
    },
  },
   
};
</script>

<style></style>
