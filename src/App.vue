<template>
  <div>
    <Tprofile/>
    <About/>
    <SKill/>
  </div>
</template>

<script>
import Tprofile from './components/Top_profile.vue'
import About from './components/about.vue'
import SKill from './components/skill.vue'
export default {
  name: 'App',
  components: {
    Tprofile,
    About,
    SKill
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
