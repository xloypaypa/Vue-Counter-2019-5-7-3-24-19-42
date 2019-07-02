<template>
  <div id="app">
    <span>{{counter}}</span>
    <button v-on:click="counter += 1">+</button>
    <button v-on:click="counter -= 1">-</button>
  </div>
</template>

<script>

export default {
  name: 'app',
  data() {
    return {
      counter: 0,
    }
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
