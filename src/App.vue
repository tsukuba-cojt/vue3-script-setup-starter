<template>
  <div id="app">
    <input type="text" v-model="message" />
    <div id="message">{{ message }}</div>
  </div>
</template>

<script setup>
import { ref } from 'vue'
const message = ref()
</script>

<style>
#message {
  background-color: #efefef;
  padding: 1rem;
  margin: 1rem 0;
}
</style>
