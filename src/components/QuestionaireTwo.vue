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
                      v-model="selected2" /><span
                      class="option agree max"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="3"
                      v-model="selected2" /><span
                      class="option agree min"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="2"
                      v-model="selected2" /><span
                      class="option neutral"
                    ></span></label
                  ><label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="1"
                      v-model="selected2" /><span
                      class="option disagree min"
                    ></span
                  ></label>
                  <label
                    ><input
                      type="radio"
                      :name="inlineRadioOptions2"
                      :value="0"
                      v-model="selected2" /><span
                      class="option disagree max"
                    ></span
                  ></label>
                </div>
                <div class="caption disagree">Disagree</div>
              </div>
              <h4>Option selected: {{ selected2 }}</h4>
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
