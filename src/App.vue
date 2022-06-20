<template>
  <div id="app">
    <HeroJumbotrone>
      
    </HeroJumbotrone>
    <TitleExercise></TitleExercise>
  </div>
</template>

<script>
import TitleExercise from './components/TitleExercise.vue'
import HeroJumbotrone from './components/HeroJumbotrone.vue'

export default {
  name: 'App',
  components: {
    TitleExercise,
    HeroJumbotrone,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}
</style>
