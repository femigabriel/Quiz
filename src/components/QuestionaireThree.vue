<template>
  <form class="form">
    <div class="Step1">
      <div class="row">
        <div class="test-questions comp">
          <div id="question1">
            <div class="question">
              <div class="qn-no">11</div>
              <div class="statement">I constantly crave new experiences.</div>
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
              <div class="qn-no">12</div>
              <div class="statement">
                I make sure I am responsible for every action and decision I
                make.
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
              <div class="qn-no">14</div>
              <div class="statement">
                I am a fun-loving person who doesn’t take life too seriously.
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
              <div class="qn-no">15</div>
              <div class="statement">
                When there is a project, I put 100% of my commitment into
                getting the work done.
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
.form {
  margin: 1.3em auto;
  background: #412167;
  border-radius: 0.5em;
  box-shadow: 0 5px 15px rgb(0 0 0 / 30%);
  padding: 1em;
  max-width: 600px;
  display: block;
  color: #fff;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
}
form div div {
  margin: 1rem 0;
}

.row {
  display: flex;

  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}

.test-questions.comp {
  margin: 0 auto;
  width: 100%;
  max-width: 900px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 15px;
}
.test-questions.comp .question {
  padding: 15px 0 20px;
  width: 100%;
  border-bottom: 1px solid #dcdcdc;
  font-family: "Raleway", sans-serif;
  transition: opacity 0.5s ease-in-out;
}
.qn-no {
  display: block;
  position: relative;
  margin: auto;
  height: 22px;
  width: 22px;
  background: #412168;
  border-radius: 20px;
  border: 1px solid;
  color: #fff;
  font-weight: 700;
  text-align: center;
  line-height: 1em;
  padding: 3px;
  font-size: 12px;
}

.test-questions.comp .question .statement {
  font-size: 1.2em;
  color: #fff;
  font-weight: 600;
  text-align: center;
  line-height: 1.5;
  margin: 0.25em auto 1em;
}

.test-questions.comp .question .decision {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 30px 0 15px;
}
.test-questions.comp .question .decision .caption.agree {
  color: #00ff9a;
}
.test-questions.comp .question .decision .caption {
  font-weight: 600;
  font-size: 0.8em;
  text-transform: uppercase;
}
.test-questions.comp .question .decision .caption.agree:hover {
  color: #00ff9a;
  transition: ease-in;
}
.test-questions.comp .question .decision .options {
  flex: 0 0 65%;
  margin: 0 15px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
label {
  display: inline-block;
  margin-bottom: 0.5rem;
}
[type="radio"] {
  position: absolute;
  opacity: 0;
  width: 0;
}
form input {
  color: white;
  display: block;
  margin: auto;
  max-width: 400px;
  background: none;
  border-radius: 0.5em;
  box-shadow: none;
  font-size: 1em;
}

.test-questions.comp .question .decision .options .option.max {
  flex: 0 0 45px;
  width: 100%;
  width: 45px;
  height: 45px;
}
.test-questions.comp .question .decision .options .option.agree {
  border: 2px solid #00ff9a;
}
.test-questions.comp .question .decision .options .option.agree:hover {
  border: 2px solid #00ff9a;
  color: #00ff9a;
  transition: ease-in;
}
.test-questions.comp .question .decision .options .option {
  border-radius: 50%;
  cursor: pointer;
  transition: all 0.1s ease-in-out;
  display: flex;
  align-items: center;
  justify-content: center;
}
label {
  display: inline-block;
  margin-bottom: 0.5rem;
}
.test-questions.comp .question .decision .options .option.min {
  flex: 0 0 28px;
  width: 28px;
  height: 28px;
}
.test-questions.comp .question .decision .options .option.agree {
  border: 2px solid #00ff9a;
}

.test-questions.comp .question .decision .options .option.neutral {
  border: 2px solid #9b9faa;
  flex: 0 0 25px;
  width: 25px;
  height: 25px;
}
.test-questions.comp .question .decision .options .option.min {
  flex: 0 0 28px;
  width: 28px;
  height: 28px;
}
.test-questions.comp .question .decision .options .option.disagree {
  border: 2px solid #bb1c1c;
}
.test-questions.comp .question .decision .options .option.disagree:hover {
  border: 2px solid #bb1c1c;
  transition: all 0.1s ease-in-out;
  cursor: pointer;
}

.test-questions.comp .question .decision .options .option.max {
  flex: 0 0 45px;
  width: 45px;
  height: 45px;
}
.test-questions.comp .question .decision .options .option.disagree {
  border: 2px solid #bb1c1c;
}
.test-questions.comp .question .decision .options .option.disagree {
  border: 2px solid #bb1c1c;
}

form button.continue {
  font-family: "Raleway", sans-serif;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  background: #904be6;
  border-radius: 50px;
  min-width: 280px;
  border: 0;
  margin: auto;
  color: #fff;
  font-size: 1.5rem;
  padding: 0.6rem 1rem;
  box-shadow: 2px 2px 5px #000;
  display: flex;
  justify-content: center;
  transition: 0.4s;
  cursor: pointer;
}
</style>
