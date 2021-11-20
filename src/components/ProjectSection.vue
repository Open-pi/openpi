<script>
  import { marked } from 'marked';

  export default {
    props: {
      imgURL: String,
      projectDesc: String,
    },
    computed: {
      markdownToHTML() {
        return marked(this.projectDesc);
      },
    },
  };
</script>

<template>
  <div class="project">
    <div class="image">
      <img :src="imgURL" />
    </div>
    <div class="desc"><div v-html="markdownToHTML"></div></div>
  </div>
</template>

<style scoped>
  .project {
    padding-left: 230px;
    padding: 23px;
    margin: 0 20em;

    display: grid;
    grid-template-columns: 7fr 6fr;
    grid-template-columns: repeat(auto-fill, 7fr 6fr);

    background-color: rgba(255, 255, 255, 0.3);
    border: solid black;
  }
  .image {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  img {
    border-radius: 50%;
    width: 200px;
  }
  .desc {
    text-align: left;
  }
</style>
