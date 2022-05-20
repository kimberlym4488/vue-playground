<template>
  <img alt="Samus" src="./assets/SamusMoran.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <TestStuff msg="This is the Test" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import TestStuff from "./components/TestStuff.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    TestStuff,
  },
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
