<template>
<header class="header">
        <div class="header-main">
            <div class="logo"> </div>
        </div>
        <div class="header-title">
            <h1 class="header-tag">Jungian Archetype Quiz</h1>
            <h2 class="h2_3TgGl">Free Archetype Quiz Reveals Your Personality Quirks, Innate Talents, and Hidden
                Weaknesses!</h2>
            <div class="arrow-down-container"><i class="fas fa-arrow-down fa-2x"></i>

            </div>
        </div>
        </header>
         <button v-for="tab in tabs" :key="tab" :class="['tab__button', { active: currentTab === tab }]" @click="currentTab = tab">
		{{tab}}
	</button>
	
	<component :is="tabSelected"></component>
</template>

<script>
export default {
    
}
</script>
<style>
.header-main {
    width: 100%;
    background: #fff;
    margin-bottom: 15px;
    border-bottom: 3px solid #904be6;
}

.header, .htext_zC6o- {
	display: flex;
	flex-direction: column;
	align-items: center;
	
}

.logo {
    margin: 1em auto;
    width: 250px;
    height: 2.8em;
	position: relative;
	background-image: url(data:image/webp;base64,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);
    background-size: cover;
}
.header-title {
    width: 90%;
    margin: 2em auto;
	text-align: center;
}
.header-tag {
  font-size: 2.5em;
   letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: .5em;
  font-family: Raleway,sans-serif;
    color: #000;
    font-weight: 700;
    color: #fff;
    text-shadow: 2px 2px 4px #000;
     text-shadow: none;
    filter: none;
      text-align: center;
}
</style>