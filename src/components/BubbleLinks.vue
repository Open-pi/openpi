<script setup>
import { ref } from 'vue'
</script>

<template>
  <div class="links">
    <a class="bubble github-link" href="https://github.com/Open-pi">
      <img class="icon" src="../assets/github.svg" alt="github-icon">
    </a>
  </div>
</template>

<style scoped>
* {
  align-content: center;
}
.icon {
  width: 80%;
  margin: auto;
}

.github-link {
  background-color: var(--purple);
  border-radius: 50px;
  width: 80px;
  height: 80px;
  display: grid;
  margin: auto;
}
</style>
