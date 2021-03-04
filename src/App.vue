<template>
  <div id="app">
    <header>
      <h1>{{sitename}}</h1>
      <button @click="showCheckout">{{ this.cart.length }}Checkout</button>
    </header>
  </div>
</template>
<script>
export default {
  name: "App",
  data() {
    return {
      sitename: "Vue.js Pet Depot",
cart: [] }
},
  methods: { showCheckout() {} }
};
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
