<template>
  <div id="app">
    <OrderSummary />
  </div>
</template>

<script>
import OrderSummary from './components/OrderSummary.vue'

export default {
  name: 'App',
  components: {
    OrderSummary
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
