<script setup>
import TextIcon from "./TextIcon.vue";
import BubleLinks from "./BubbleLinks.vue";
</script>

<template>
  <h1>
    <span class="welcome">Welcome to </span
    ><span class="icon"><TextIcon /></span>
  </h1>
  <p>Check out our open-source projects :)</p>
  <BubleLinks />
</template>

<style scoped>
h1 {
  color: var(--purple);
  font-size: 40px;
}

.icon {
  font-size: 40px;
  color: var(--yellow);
  color: white;
  background-color: var(--purple);
}

.welcome {
  background-color: white;
}

img {
  width: 10%;
}
</style>
