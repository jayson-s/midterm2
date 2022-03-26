<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <p>
    <a href="https://jsonplaceholder.typicode.com/users" target="_blank">Home</a>
    |
    <a href="https://jsonplaceholder.typicode.com/todos" target="_blank">Tasks</a>
    |
    <a href="https://jsonplaceholder.typicode.com/users" target="_blank">Login</a>
  </p>

  
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
