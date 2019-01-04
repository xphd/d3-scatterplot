<template>
  <div id="app">
    <Scatterplot/>
  </div>
</template>

<script>
import Scatterplot from "./components/Scatterplot.vue";

export default {
  name: "app",
  components: {
    Scatterplot
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
