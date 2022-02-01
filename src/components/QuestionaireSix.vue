<template>
  <form class="form">
    <div class="Step1">
      <div class="row">
        <div class="test-questions comp">
          <div id="question1">
            <div class="question">
              <div class="form-title">
                <p>
                  Thank <strong>you</strong> for
                  <strong>your</strong> participation!
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
   
    <div class="div">
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
    previous() {
      this.$emit("gotoPrevious");
    },
  },
};
</script>

<style></style>
