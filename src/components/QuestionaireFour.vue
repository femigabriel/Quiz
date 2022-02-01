<template>
  <form class="form">
    <div class="Step1">
      <div class="row">
        <div class="test-questions comp">
          <div id="question1">
            <div class="question">
              <div class="qn-no">16</div>
              <div class="statement">
                I never doubt the great things I am capable of.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                <div class="options">
                  <label
                    ><input
                      type="radio"
                      name="inlineRadioOptions31"
                      value="4" /><span class="option agree max"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions31"
                      value="3" /><span class="option agree min"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions31"
                      value="2" /><span class="option neutral"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions31"
                      value="1" /><span
                      class="option disagree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions31"
                      value="0" /><span class="option disagree max"></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
            </div>
            <div class="question">
              <div class="qn-no">17</div>
              <div class="statement">
                As a team member, I am here when you need me for support, making
                sure others’ leadership stands out.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                <div class="options">
                  <label
                    ><input
                      type="radio"
                      name="inlineRadioOptions17"
                      value="4" /><span class="option agree max"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions17"
                      value="3" /><span class="option agree min"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions17"
                      value="2" /><span class="option neutral"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions17"
                      value="1" /><span
                      class="option disagree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions17"
                      value="0" /><span class="option disagree max"></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
            </div>
            <div class="question">
              <div class="qn-no">18</div>
              <div class="statement">
                I seek to break norms, especially when they don’t make sense at
                all.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                <div class="options">
                  <label
                    ><input
                      type="radio"
                      name="inlineRadioOptions21"
                      value="4" /><span class="option agree max"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions21"
                      value="3" /><span class="option agree min"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions21"
                      value="2" /><span class="option neutral"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions21"
                      value="1" /><span
                      class="option disagree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions21"
                      value="0" /><span class="option disagree max"></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
            </div>
            <div class="question">
              <div class="qn-no">19</div>
              <div class="statement">
                I can lead people into meaningful action that produces progress
                and results.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                <div class="options">
                  <label
                    ><input
                      type="radio"
                      name="inlineRadioOptions25"
                      value="4" /><span class="option agree max"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions25"
                      value="3" /><span class="option agree min"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions25"
                      value="2" /><span class="option neutral"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions25"
                      value="1" /><span
                      class="option disagree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions25"
                      value="0" /><span class="option disagree max"></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
            </div>
            <div class="question">
              <div class="qn-no">20</div>
              <div class="statement">
                I constantly crave new knowledge, as I value them a lot.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                <div class="options">
                  <label
                    ><input
                      type="radio"
                      name="inlineRadioOptions27"
                      value="4" /><span class="option agree max"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions27"
                      value="3" /><span class="option agree min"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions27"
                      value="2" /><span class="option neutral"></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions27"
                      value="1" /><span
                      class="option disagree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      name="inlineRadioOptions27"
                      value="0" /><span class="option disagree max"></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
            </div>
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

<style>

</style>
