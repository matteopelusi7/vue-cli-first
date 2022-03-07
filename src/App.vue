<template>
  <div id="app">
   <TitleCli />
   <heroJumbo />
  </div>
</template>

<script>

import TitleCli from './components/Title.vue'
import heroJumbo from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    TitleCli,
    heroJumbo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
