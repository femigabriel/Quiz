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
                 <p v-if="errors.length > 0">
                  {{errors}}
                  <ul class="errorMsg">
                 <li v-for="e in errors" :key="e">
                 {{ e }}
                 </li>
                 </ul>
                </p>
            
     <div class="divider"></div>
		<div class="step div">
			<div class="item">
				<div class="div">
					<input
						type="text"
						id="name"
						name="name"
						placeholder="Name"
						required=""
						v-model="name"
					/>
				</div>
			</div>
			</div>
              <div class="step div">
                <div class="item">
                  <div class="div">
                   <input
						type="email"
						id="email"
						name="email"
						placeholder="Email"
						required=""
						v-model="email"
                    />
                  </div>
                </div>
              </div>
             
            </div>
          </div>
          </div>
        </div>
      </div>
    
 <div class="div">
      <button @click="saveData" type="button" class="continue">
        <span class="span"
          >See My Results <i class="fa fa-angle-right" ></i
        ></span>
         </button>
            <br>
    </div>
     <div class="previous">
        <button @click="previous" type="button" class="continue">
        <span class="span"
          >PREVIOUS <i class="fa fa-angle-right" ></i
        ></span>
      </button>
    </div>
     
  </form>
</template>
<script>
export default {
  data() 
  {
    return {
    errors: [],
    name: null,
    email: null
  
    }
   
  },
  emits: [],
  methods: {
    saveData() {

    if(this.name && this.email)
    this.errors=[];
    if(!this.name)
    {
      this.errors.push("please input your name")
    }
     if(!this.email)
     {
      this.errors.push("please input your email")
    }
    
    

      if (this.errors.length < 1 ) {
        this.$emit("submitForm");
      }
    },
     previous() {
      this.$emit("gotoPrevious");
      
    },
  },
   
};
</script>

<style scoped>
h2 {
    font-size: 1.2em;
    font-family: Raleway,sans-serif;
	font-weight: 500;
    line-height: 1.2;
    color: inherit;
	margin-bottom: .5rem;
	margin-top: 0;
}
form h2 {
    color: #fff;
    margin-bottom: 0;
    filter: drop-shadow(0 0 5px #904be6);
    text-shadow: 0 0 5px purple, 0 0 10px purple, 0 0 20px purple;
}
form .seperator_2B5q5 {
    width: 100%;
    height: 5px;
    background: #904be6;
    box-shadow: 2px 2px 5px #000;
    margin: 0 auto;
}
input[type=text], input[type=email] {
    background: rgba(0,0,0,.3);
    box-shadow: 0 0 5px #fff;
}
form input, form select, form input:hover, form input:focus, select:focus, form select:active {
    color: white;
    padding: 1em;
    background: none;
    border-radius: .5em;
    
}
form input, form select {
    font-size: 1em;
   border: 0;
    display: block;
    margin: auto;
    max-width: 400px;
    text-transform: capitalize;
    width: 100%;
    font-family: 'Raleway',sans-serif;
    font-weight: 300;
    box-sizing: border-box;
}
button, input {
    overflow: visible;
}
.divider {
    height: 1px;
    width: 100%;
    background: #fff;
    margin: 0 auto;
    max-width: 400px;
}
</style>
