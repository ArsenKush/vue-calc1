<template>
  <div id="app">
    <MyCalc />
  </div>
</template>

<script>
import MyCalc from "./components/MyCalc.vue";

export default {
  name: "app",
  components: {
    MyCalc,
  },
};
</script>

<style>
html,
body {
  padding: 0;
  margin: 0;
  background-color: #2c3e50;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#app {
  margin-top: 60px;
}
</style>
