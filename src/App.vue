<template>
  <div id="app">
    <h1>Terminology Services Let's Build!</h1>
    <TermDemo bodyPart="{ 'system': 'mySystem', 'code': '12345', 'display': 'Tongue' }"/>
  </div>
</template>

<script>
import TermDemo from './components/TermDemo.vue'


export default {
  name: 'app',
  components: {
    TermDemo
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
