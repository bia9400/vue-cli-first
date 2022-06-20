<template>
  <div id="app">
    <TitleExercise></TitleExercise>
  </div>
</template>

<script>
import TitleExercise from './components/TitleExercise.vue'

export default {
  name: 'App',
  components: {
    TitleExercise
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
  margin-top: 60px;
}
</style>
