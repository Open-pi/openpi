<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Title from './components/Title.vue'
import MissionStatement from './components/MissionStatement.vue'
import TopBar from './components/TopBar.vue'
</script>

<template>
  <div class="landing-screen">
    <div class="topbar">
      <TopBar/>
    </div>

    <Title/>
  </div>

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

:root {
  --purple: #887BB0;
  --dark-purple: #342837;
  --spearmint: #85D2D0;
  --rosequartz: #F4B9B8;
  --yellow: #FFF4BD;
}

#app {
  font-family: Inter, Metropolis;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.landing-screen {
  padding-top: 25px;
  height: 100vh;

  background-image: url('./assets/mountains-1412683.svg');
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
  -webkit-background-size: cover;
  -moz-background-size:cover;
  -o-background-size:cover;
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
