<template>
  <div id="app">
    <!--img alt="Vue logo" src="./assets/logo.png"--> 
    <Title msg="La mia prima app con Vue CLI!"/>
    <JumboTron/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    Title,
    JumboTron,
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
