<template>
  <div id="app">
    <GradationBtn msg="sample" url="#" :color="''" :fontSize="''" :padding="''" :bgGradation="''" :borderColor="''"/>
    <LineAnimation msg="lineAnimation" url="#" :bgGradation="''" :borderColor="''"/>
    <LineAnimation02 msg="lineAnimation02" url="#"/>
    <LineAnimation03 msg="副産物" url="#"/>
  </div>
</template>

<script>
import GradationBtn from './components/gradation_btn.vue'
import LineAnimation from './components/lineanimation_btn.vue'
import LineAnimation02 from './components/LineAnimation02.vue'
import LineAnimation03 from './components/LineAnimation03.vue'

export default {
  name: 'app',
  components: {
    GradationBtn,
    LineAnimation,
    LineAnimation02,
    LineAnimation03
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
