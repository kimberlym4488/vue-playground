<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <TestStuff msg="This is testStuff" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import TestStuff from "@/components/TestStuff.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    TestStuff,
  },
};
</script>
