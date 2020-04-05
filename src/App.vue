<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Button btnType="Detail" />
    <Button btnType="Order" />
    <Button btnType="Favorite" />

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Button from './components/Button.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Button
  }
}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
</style>
