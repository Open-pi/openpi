<script setup>
  import LineBar from './LineBar.vue';
  import ProjectSection from './ProjectSection.vue';
</script>

<template>
  <div class="projects-section">
    <h1><span id="span1">Here's our </span><span id="span2">projects</span></h1>
    <p>All of them are open source! :)</p>
    <LineBar style="background-color: var(--dark-purple); height: 125px" />
    <ProjectSection
      img-u-r-l="src/assets/spellingwizard.png"
      project-desc="# SpellingWizard

Spelling is one of those things that are particularly crucial in the English language.
If you are preparing for a test or improving your skill, **SpellingWizard** is your friend.

**SpellingWizard** is simple yet feature rich spelling app. 
As opposed to other spelling apps that have a robotic voice to pronounce the words and an archaic user experience, SW has :
* a **userfriendly**, and **beautiful** interface (as well as addtional themes to choose from)
* An **awesome** and **clear** human voice.

[<img src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' alt='Get it on Google Play' height='80'>](https://play.google.com/store/apps/details?id=com.opensegmentationsystems.spellingwizards)
[<img src='https://fdroid.gitlab.io/artwork/badge/get-it-on.png' alt='Get it on F-Droid' height='80'>](https://f-droid.org/packages/com.openpi.spellingwizard)"
    ></ProjectSection>

    <LineBar style="background-color: var(--dark-purple); height: 125px" />
  </div>
</template>

<style scoped>
  * {
    padding: 0;
    margin: 0;
  }

  .projects-section {
    background: rgb(255, 194, 198);
    background: linear-gradient(
      90deg,
      rgba(255, 194, 198, 1) 0%,
      rgba(255, 194, 198, 1) 30%,
      rgba(255, 225, 207, 1) 100%
    );
    min-height: 100vh;
  }

  h1 {
    padding: 5em 0 0.5em 0;
    font-size: 40px;
  }

  #span1 {
    background-color: white;
  }
  #span2 {
    background-color: var(--spearmint);
  }
</style>
