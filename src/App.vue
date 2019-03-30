<template>
  <div id="app">
    <RubberDuck/>
  </div>
</template>

<script>
import RubberDuck from '@/components/RubberDuck'
export default {
  name: 'app',
  components: {
    RubberDuck
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
