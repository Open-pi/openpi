<script setup>
import { ref } from 'vue'
import TextIcon from './TextIcon.vue'
</script>

<template>
  <nav class="grid-container">
    <div class="logo grid-items">
      <span><TextIcon/></span>
    </div>

    <a class="menu grid-items nav-item">
      <span>Home Page</span>
    </a>

    <a class="projects grid-items nav-item">
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
}

.grid-container {
  display: grid;
  grid-template-columns: 7fr 1fr 1fr 1fr;

}

.grid-items {
  display: grid;
  margin-right: 10px;
}

.grid-items span{
  margin: auto;
  padding-top: 6px;
  padding-bottom: 6px;
}

.logo {
  text-align: left;
  padding-left: 100px
}

.logo span {
  text-align: left;
  margin: auto 0 0 0;
}

.nav-item {
  border-radius: 50px;
  background-color: #42b983;
  border: 2px solid #42b983;
  color: white;
}

</style>
