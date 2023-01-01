<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import newss from "./components/newss.vue";
</script>

<template>
  <HelloWorld msg="Vite + Vue" />
  <newss ggb="Vite + Vue" />
</template>

<style scoped>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #8b64ffaa);
  }
  .logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
  }
</style>
