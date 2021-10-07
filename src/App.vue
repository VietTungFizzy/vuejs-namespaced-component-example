<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <CallComponent/>
</template>

<script>
import CallComponent from './components/CallComponent.vue'

export default {
  name: 'App',
  components: {
    CallComponent
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
