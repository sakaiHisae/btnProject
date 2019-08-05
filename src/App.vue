<template>
  <div id="app">
    <LineAnimation00 msg="lineAnimation00" url="#" :color="''" :fontSize="''" :padding="''" :bgGradation="''" :borderColor="''"/>
    <LineAnimation01 msg="lineAnimation01" url="#" :bgGradation="''" :borderColor="''"/>
    <LineAnimation02 msg="lineAnimation02" url="#"/>
    <LineAnimation03 msg="lineAnimation03" url="#"/>
    <LineAnimation04 msg="lineAnimation04" url="#"/>
  </div>
</template>

<script>
import LineAnimation00 from './components/LineAnimation00.vue'
import LineAnimation01 from './components/LineAnimation01.vue'
import LineAnimation02 from './components/LineAnimation02.vue'
import LineAnimation03 from './components/LineAnimation03.vue'
import LineAnimation04 from './components/LineAnimation04.vue'

export default {
  name: 'app',
  components: {
    LineAnimation00,
    LineAnimation01,
    LineAnimation02,
    LineAnimation03,
    LineAnimation04
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
