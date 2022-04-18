<template>
  <div id="mainSkills">
    <h1>Skills</h1>
    <div id="skillsContaier">
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="skill">
        <GitHubSVG />
      </div>
      <div id="clear"></div>
    </div>
  </div>
</template>

<script>
/* eslint-disable */
import GitHubSVG from "../components/SVG/GitHub.vue";

export default {
  name: "Skills",
  components: {
    GitHubSVG,
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

#mainSkills {
  width: 85%;
  margin: auto;
  line-height: 25px;
  margin-bottom: 50px;
}

#skillsContaier {
  margin: auto;
  width: 80%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}

#skill {
  margin: 18px;
  float: left;
  background-color: white;
  border-radius: 100px;
  display: flex;
  align-items: center;
  width: fit-content;
}

#clear {
  float: none;
}
</style>
