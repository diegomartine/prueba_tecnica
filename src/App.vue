<template>
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
}

#app {
  background-color: #1f1e1e;
  min-height: 100vh;
  margin: 0;
  padding: 0;
  width: 100%;
  box-sizing: border-box;
}
</style>

