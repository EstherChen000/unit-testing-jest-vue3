<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <RandomNumber />
    <MessageDisplay />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import RandomNumber from "@/components/RandomNumber.vue";
import MessageDisplay from "@/components/MessageDisplay.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    RandomNumber,
    MessageDisplay,
  },
};
</script>
