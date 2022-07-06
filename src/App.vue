<template>
  <div id="app">
    <h1>Ciao</h1>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style lang="scss" scoped>
@import './style/common.scss';
@import './style/variables.scss';
h1 {
  color: $brand-color;
}
</style>
