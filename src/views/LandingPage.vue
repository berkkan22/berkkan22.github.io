<template>
  <div class="main">
    <div id="landingImg" />
    <NavBar />
    <CatchContainer id="catchContainer" />
    <a href="#mainAboute">
      <ArrowDownSVG id="arrowDown" />
    </a>
    <MainBody />
  </div>
</template>

<script>
import NavBar from "../components/Navbar.vue";
import CatchContainer from "../components/CatchContainer.vue";
import ArrowDownSVG from "../components/SVG/ArrowDown.vue";
import MainBody from "../views/MainBody.vue";

export default {
  name: "LandingPage",
  components: {
    NavBar,
    CatchContainer,
    ArrowDownSVG,
    MainBody,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#landingImg {
  width: 100%;
  height: 110vh;
  background: linear-gradient(to top, #000000ba, #000000ba),
    url(../assets/landingpage.jpg) no-repeat top center;
}

#catchContainer {
  position: absolute;
  top: 225px;
  right: 180px;
  display: flex;
  align-items: center;
  flex-direction: column;
}

#arrowDown {
  position: absolute;
  bottom: 50px;
  right: 50%;
}
</style>
