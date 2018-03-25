<template>
  <div id="app">
   <h1>Welcome to AppyApp!</h1>
    <skills skill="This is my skill!"/>
    <DansComponent/>
  </div>
</template>

<script>
import skills from './components/skills.vue';
 import djs from './components/djs_component.vue'; 

export default {
  name: 'app',
  components: {
    skills,
    'DansComponent':djs
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
