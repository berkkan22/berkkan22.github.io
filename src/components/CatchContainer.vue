<template>
  <div id="main">
    <div id="quoatContainer">
      <div id="catchText">
        <span>I am a </span>
        <span id="dev">Developer</span>
      </div>
      <div id="quoat">
        <p>
          Programming is a skill that is best acquired through practice and
          examples, not books.
        </p>
      </div>
    </div>
    <div id="authorContainer">
      <div id="line"></div>
      <span id="author">Alan Turing</span>
      <div id="line"></div>
    </div>
    <div id="clear"></div>
    <div id="social">
      <GitHubSVG />
      <InstagramSVG />
      <SnapchatSVG />
      <img src="../assets/gmail.png" alt="" srcset="" />
    </div>
  </div>
</template>

<script>
import GitHubSVG from "../components/SVG/GitHub.vue";
import InstagramSVG from "../components/SVG/Instragram.vue";
import SnapchatSVG from "../components/SVG/Snapchat.vue";

export default {
  name: "CatchContainer",
  components: {
    GitHubSVG,
    InstagramSVG,
    SnapchatSVG,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#quoatContainer {
  /* margin-bottom: 95px; */
}

span {
  font-size: 80px;
  color: white;
}

#dev {
  color: #5e72eb;
  font-weight: bold;
}

#quoat {
  /* margin-top: 60px;
  margin-bottom: 25px; */
  color: white;
  text-align: center;
  font-size: 35px;
  width: 618px;
  line-height: 61px;
}

#authorContainer {
  width: 365px;
  margin: auto;
}

#author {
  font-family: "Parisienne", Avenir, Helvetica, Arial, sans-serif;
  float: left;
  font-size: 28px;
}

#line {
  width: 75px;
  height: 5px;
  float: left;
  background-color: #5e72eb;
  margin-top: 9px;
  margin-left: 15px;
  margin-right: 15px;
}

#social {
  display: flex;
  gap: 36px;
}
</style>
