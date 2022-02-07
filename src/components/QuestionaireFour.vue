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
                      v-model="selected16" /><span
                      class="option agree max"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="2"
                      :value="3"
                      v-model="selected16" /><span
                      class="option agree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="2"
                      v-model="selected16" /><span
                      class="option neutral"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="1"
                      v-model="selected16" /><span
                      class="option disagree min"
                    ></span
                  ></label>
                  <label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="0"
                      v-model="selected16" /><span
                      class="option disagree max"
                    ></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
              <h4>Option Selected: {{ selected16 }}</h4>
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
                    v-model="selected17" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="3"
                    v-model="selected17" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="2"
                    v-model="selected17" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="1"
                    v-model="selected17" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="0"
                    v-model="selected17" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option selected: {{ selected17 }}</h4>
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
                    v-model="selected18" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="3"
                    v-model="selected18" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="2"
                    v-model="selected18" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="1"
                    v-model="selected18" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="0"
                    v-model="selected18" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option selected: {{ selected18 }}</h4>
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
                    v-model="selected19" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="3"
                    v-model="selected19" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="2"
                    v-model="selected19" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="1"
                    v-model="selected19" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="0"
                    v-model="selected19" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option selected: {{ selected19 }}</h4>
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
                    v-model="selected20" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="3"
                    v-model="selected20" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="2"
                    v-model="selected20" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="1"
                    v-model="selected20" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="0"
                    v-model="selected20" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
           
          </div>
           <h4>Option Selected: {{ selected20 }}</h4>
            <p v-if="errors.length > 0">
            <ul class="errorMsg">
  <li v-for="e in errors" :key="e">
    {{ e }}
  </li>
</ul>
             
            </p>
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
      selected20: "",
      selected19: "",
      selected18: "",
      selected17: "",
      selected16: "",

      errors: [],
      options: "",
    };
  },
  emits: [],
  methods: {
    previous() {
      this.$emit("gotoPrevious");
    },
    saveData(e) {
      if (!this.selected16) 
      {
        this.errors.push("please Attempt Question 16");
      }

      if (!this.selected17) {
        this.errors.push("please Attempt Question 17");
      }

      if (!this.selected18) {
        this.errors.push("please Attempt Question 18");
      }

      if (!this.selected19) {
        this.errors.push("please Attempt Question 19");
      }

      if (!this.selected20) {
        this.errors.push("Please Attempt Question 20");
      }

      console.warn("errors", this.errors);
      e.preventDefault();
      
      if (this.errors.length < 1 ) {
        this.$emit("gotoNext");
        
      }
    
    
    },
    
  },
};
</script>
<style>

</style>
