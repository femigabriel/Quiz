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
                      :name="inlineRadioOptions1"
                      :value="4"
                      v-model="selected1" /><span
                      class="option agree max"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="2"
                      :value="3"
                      v-model="selected1" /><span
                      class="option agree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="2"
                      v-model="selected1" /><span
                      class="option neutral"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="1"
                      v-model="selected1" /><span
                      class="option disagree min"
                    ></span
                  ></label>
                  <label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="0"
                      v-model="selected1" /><span
                      class="option disagree max"
                    ></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
              <h4>Option Selected: {{ selected1 }}</h4>
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
                    :name="inlineRadioOptions3"
                    :value="4"
                    v-model="selected3" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="3"
                    v-model="selected3" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="2"
                    v-model="selected3" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="1"
                    v-model="selected3" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="0"
                    v-model="selected3" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option selected: {{ selected3 }}</h4>
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
                    :name="inlineRadioOptions3"
                    :value="4"
                    v-model="selected3" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="3"
                    v-model="selected3" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="2"
                    v-model="selected3" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="1"
                    v-model="selected3" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="0"
                    v-model="selected3" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option selected: {{ selected3 }}</h4>
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
                    :name="inlineRadioOptions4"
                    :value="4"
                    v-model="selected4" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="3"
                    v-model="selected4" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="2"
                    v-model="selected4" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="1"
                    v-model="selected4" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="0"
                    v-model="selected4" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option selected: {{ selected4 }}</h4>
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
                    :name="inlineRadioOptions5"
                    :value="4"
                    v-model="selected5" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="3"
                    v-model="selected5" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="2"
                    v-model="selected5" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="1"
                    v-model="selected5" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="0"
                    v-model="selected5" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option Selected: {{ selected5 }}</h4>
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
  data() {
    return {
      selected5: "",
      selected4: "",
      selected3: "",
      selected2: "",
      selected1: "",
    };
  },
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
