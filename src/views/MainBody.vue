<template>
  <div id="main">
    <About />
    <Skills />
    <Projects />
  </div>
</template>

<script>
import About from "../views/About.vue";
import Skills from "../views/Skills.vue";
import Projects from "../views/Projects.vue";

export default {
  name: "MainBody",
  components: {
    About,
    Skills,
    Projects,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#main {
  width: fit-content;
  max-width: 1000px;
  margin: auto;
  background-color: #0b0742;
  padding-bottom: 50px;
  position: absolute;
  top: 100vh;
  left: 50%;
  transform: translate(-50%, 0px);
}
</style>
