<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <Hello msg="Hello Vue in CodeSandbox!"/>
  </div>
</template>

<script>
import Hello from "./views/home/index";

export default {
  name: "App",
  components: {
    Hello
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
