<template>
  <div id="app">
    <Header />
    <Questionaire v-show="current == 0" @gototwo="current = current + 1" />
    <QuestionaireTwo v-show="current == 1" @gotothree="current = current + 1" />
    <QuestionaireThree v-show="current == 2" @gotofour="current = current + 1" />
    <QuestionaireFour v-show="current == 3" @gotofive="current = current + 1" />
    <QuestionaireFive v-show="current == 4" @gotosix="current = current + 1" />
  </div>
</template>

<script>
import Header from "./components/Header";
import Questionaire from "./components/Questionaire";
import QuestionaireTwo from "./components/QuestionaireTwo";
import QuestionaireThree from "./components/QuestionaireThree";
import QuestionaireFour from "./components/QuestionaireFour";
import QuestionaireFive from "./components/QuestionaireFive";


export default {
  name: "App",
  components: {
    Header,
    Questionaire,
    QuestionaireTwo,
    QuestionaireThree,
    QuestionaireFour,
    QuestionaireFive

  },

  data () {
    return {
current: 0
    }
  },
};
</script>

<style>
*,
::after,
::before {
  box-sizing: border-box;
}

body {
  background-color: #000;
  background: url(https://individualogist.com/wp-content/uploads/archetype-wheel-overlay.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #fff;
  text-align: left;
}

#app {
}
</style>
