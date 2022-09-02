<template>
  <div id="app"><HelloWorld></HelloWorld></div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      orbit1: 40,
      orbit2: 0.8,
      orbit3: 0.7,
      rot1: 0,
      rot2: -1,
      rot3: 0,
      width: 50,
      height: 50,
      depth: 50
    };
  },
  created() {}
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
