<template>
  <div id="app">
    <gradient-color />
    <home />
  </div>
</template>

<script>
import Home from "./view/Home.vue";
import GradientColor from "./view/GradientColor";
export default {
  name: "App",
  components: {
    Home,
    GradientColor
  }
};
</script>

<style>
@import url("https://cdn.bootcss.com/font-awesome/4.7.0/css/font-awesome.min.css");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  user-select: none;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
body {
  background-color: #aaa;
}
#app {
  position: relative;
  max-width: 375px;
  max-height: 667px;

  width: 100vw;
  height: 100vh;
  margin: 0 auto;
}
</style>
