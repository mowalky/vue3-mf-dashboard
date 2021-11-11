<script setup>
import { ref } from "vue";
const count = ref(0);
const increment = () => {
  count.value++;
};
</script>
<template>

  <div class="container">
    <v-btn @click="increment">Counter: {{count}}</v-btn>
    <div>Name: components</div>
    <div>Framework: vue3</div>
    <div>Language: JavaScript</div>
    <div>CSS: Empty CSS</div>
  </div>
</template>
