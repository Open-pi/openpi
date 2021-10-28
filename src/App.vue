<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Title from './components/Title.vue'
import MissionStatement from './components/MissionStatement.vue'
import TopBar from './components/TopBar.vue'
</script>

<template>
  <div class="topbar">
    <TopBar/>
  </div>

  <Title/>
  <!-- Comment<MissionStatement/> -->
</template>

<style>
@font-face {
  font-family: "Metropolis";
  src: url(./assets/fonts/Metropolis/Metropolis-Bold.otf)
}

@font-face {
  font-family: "Inter";
  src: url(./assets/fonts/Inter/Inter-Regular.ttf)
}
#app {
  font-family: Inter, Metropolis;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}

h1,
h2,
h3 {
  font-family: Metropolis;
}

.topbar {
  margin-bottom: 200px;
}
</style>
