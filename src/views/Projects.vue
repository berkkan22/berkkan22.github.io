<template>
  <div id="mainProjects">
    <h1>Projects</h1>
    <div id="projectContainer">
      <Project v-for="index in 10" :key="index" />
    </div>
  </div>
</template>

<script>
/* eslint-disable */
import Project from "../components/Project.vue";

export default {
  name: "Projects",
  components: {
    Project,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 0;
  padding-top: 50px;
  color: white;
  margin-bottom: 50px;
}

#mainProjects {
  width: 85%;
  margin: auto;
  line-height: 25px;
  margin-bottom: 50px;
}

#projectContainer {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  gap: 50px 35px;
}
</style>
