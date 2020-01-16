<template>
  <div id="app">
    <h1>Calculator in Vue</h1>
    <hr />
    <Calculator />
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'
export default {
  name: 'app',
  components: {
    Calculator
  }
}
</script>

<style>
#app {
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
   font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>


