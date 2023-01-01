<script setup>
import { ref } from "vue";
defineProps({
  ggb: String,
});
const TEST = ref(0);
</script>

<template>
  <h1>{{ ggb }}</h1>

  <div class="card">
    <button type="button" @click="TEST++">TEST is {{ TEST }}</button>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
