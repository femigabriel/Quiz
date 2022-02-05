<template>
  <form class="form">
    <div class="Step1">
      <div class="row">
        <div class="test-questions comp">
          <div id="question1">
            <div class="question">
              <div class="qn-no">6</div>
              <div class="statement">
                I am the life of the party and enjoy conversing with other
                people.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                 <div class="options">
                  <label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="4"
                      v-model="selected6" /><span
                      class="option agree max"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="2"
                      :value="3"
                      v-model="selected6" /><span
                      class="option agree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="2"
                      v-model="selected6" /><span
                      class="option neutral"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="1"
                      v-model="selected6" /><span
                      class="option disagree min"
                    ></span
                  ></label>
                  <label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions1"
                      :value="0"
                      v-model="selected6" /><span
                      class="option disagree max"
                    ></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
              <h4>Option Selected: {{ selected6 }}</h4>
            </div>

            <div class="question">
              <div class="qn-no">7</div>
              <div class="statement">
                I’m quite reserved at parties and delight in observing people
                rather than striking a conversation with them.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                  <div class="options">
                  <label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="4"
                      v-model="selected7" /><span
                      class="option agree max"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="3"
                      v-model="selected7" /><span
                      class="option agree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="2"
                      v-model="selected7" /><span
                      class="option neutral"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="1"
                      v-model="selected7" /><span
                      class="option disagree min"
                    ></span
                  ></label>
                  <label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="0"
                      v-model="selected7" /><span
                      class="option disagree max"
                    ></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
              <h4>Option selected: {{ selected7 }}</h4>
            </div>
          
            <div class="question">
              <div class="qn-no">8</div>
              <div class="statement">
                When meeting new people, I tend to hold back.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                <div class="options">
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="4"
                    v-model="selected8" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="3"
                    v-model="selected8" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="2"
                    v-model="selected8" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="1"
                    v-model="selected8" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions3"
                    :value="0"
                    v-model="selected8" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option selected: {{ selected8 }}</h4>
          </div>

            <div class="question">
              <div class="qn-no">9</div>
              <div class="statement">
                When making decisions, I tend to put myself in the shoes of
                other people.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
                <div class="options">
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="4"
                    v-model="selected9" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="3"
                    v-model="selected9" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="2"
                    v-model="selected9" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="1"
                    v-model="selected9" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions4"
                    :value="0"
                    v-model="selected9" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
            <h4>Option selected: {{ selected9 }}</h4>
          </div>
          
            <div class="question">
              <div class="qn-no">10</div>
              <div class="statement">
                Deep inside, I seek to invent something that will change the
                world.
              </div>
              <div class="decision">
                <div class="caption agree">Agree</div>
               <div class="options">
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="4"
                    v-model="selected10" /><span
                    class="option agree max"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="3"
                    v-model="selected10" /><span
                    class="option agree min"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="2"
                    v-model="selected10" /><span
                    class="option neutral"
                  ></span></label
                ><label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="1"
                    v-model="selected10" /><span
                    class="option disagree min"
                  ></span
                ></label>
                <label
                  ><input
                    type="radio"
                    :name="inlineRadioOptions5"
                    :value="0"
                    v-model="selected10" /><span
                    class="option disagree max"
                  ></span
                ></label>
              </div>
              <div class="caption disagree">Disagree</div>
            </div>
             <h4>Option Selected: {{ selected10 }}</h4>
          </div>
         
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
      
      selected6: "",
      selected7: "",
      selected8: "",
      selected9: "",
      selected10: "",

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
      if (!this.selected6) 
      {
        this.errors.push("please Attempt Question 6");
      }

      if (!this.selected7) {
        this.errors.push("please Attempt Question 7");
      }

      if (!this.selected8) {
        this.errors.push("please Attempt Question 8");
      }

      if (!this.selected9) {
        this.errors.push("please Attempt Question 9");
      }

      if (!this.selected10) {
        this.errors.push("Please Attempt Question 10");
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
.previous button {
  letter-spacing: 2px;
  text-transform: uppercase;
  background: #904be6;
  border-radius: 50px;
 
  border: 0;
  margin:  20px 10px;
  color: #fff;
  font-size: 1rem;
  padding: 10px 15px;
  box-shadow: 2px 2px 5px #000;
  display: flex;
  justify-content: center;
  transition: 0.4s;
  cursor: pointer;
}

.previous button:hover {
   justify-content: center;
  transition: 0.4s;
  cursor: pointer;
   background: #00ff9a;
}

</style>
