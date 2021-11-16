<script setup>
import TextIcon from "./TextIcon.vue";
</script>

<template>
  <nav class="grid-container">
    <div class="logo grid-items">
      <span><TextIcon /></span>
    </div>

    <a class="menu grid-items nav-item">
      <span>Home</span>
    </a>

    <a class="projects-link grid-items nav-item" href="#projects">
      <span>Projects</span>
    </a>

    <a class="members grid-items nav-item">
      <span>Members</span>
    </a>
  </nav>
</template>

<style scoped>
* {
  text-align: center;
}

a {
  cursor: pointer;
  text-decoration: none;
}

.grid-container {
  display: grid;
  grid-template-columns: 7fr 1fr 1fr 1fr;
  padding-right: 70px;
}

.grid-items {
  display: grid;
  margin-right: 10px;
}

.grid-items span {
  margin: auto;
  padding-top: 6px;
  padding-bottom: 6px;
}

.logo {
  text-align: left;
  padding-left: 100px;
}

.logo span {
  text-align: left;
  margin: auto 0 0 0;
  color: var(--dark-purple);
  font-size: 25px;
}

.nav-item {
  font-family: Metropolis;
  border-radius: 50px;
  color: black;
  transition: background-color 70ms ease-in-out;
  transition: border 70ms ease-in-out;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.nav-item:hover {
  color: white;
  background-color: var(--purple);
  border: 3px solid var(--rosequartz);
}
</style>
