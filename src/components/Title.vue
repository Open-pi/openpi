<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

</script>

<template>
  <h1>{{ msg }}</h1>
  <p>This Web Page is still under construction</p>
  <img alt="underconstruction" src="../assets/under-construction.png"/>
</template>

<style scoped>
h1 {
  color: #42b983;
}

img {
  width: 10%;
}
</style>
