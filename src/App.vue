<template>
  <Landscape v-if="isLandscape"/>
  <Mobile v-else/>
</template>

<script>
import Landscape from "@/components/Landscape/MainComponent.vue"
import Mobile from "@/components/Mobile/MainComponent.vue"

export default {
  name: 'App',
  data(){
    return{
      isLandscape: false
    }
  },
  components:{
    Landscape,
    Mobile
  },
  mounted(){
    this.detectScreen();
  },  
  methods: {
    detectScreen() {
      this.isLandscape = window.innerWidth > window.innerHeight;
    },
  }
}
</script>

<style>
@font-face {
  font-family: bubble;
  src: url('../public/fonts/ChoretFudyngBubble-Regular.ttf');
}
@import url('https://fonts.googleapis.com/css2?family=Concert+One&family=Exo+2:ital,wght@0,100..900;1,100..900&family=Jost:ital,wght@0,100..900;1,100..900&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

html,body{
  margin:0;
}

*{
  overflow-x:hidden;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
