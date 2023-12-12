<template>
  <HelloWorld/>
  <div id="app">
    <h1>{{ product }}</h1>
    <p>{{ productDescription }}</p>
  </div>
</template>


<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data() {
    return {
      product: 'stock', // Assign the value from $product to a local property
      productDescription: 'This is socks with blue color'
    };
  },
 
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
