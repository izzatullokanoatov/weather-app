<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <router-link to="/contact">Contact us </router-link>
    <Furniture />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Furniture from "@/components/Furniture.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Furniture
  }
};
</script>
