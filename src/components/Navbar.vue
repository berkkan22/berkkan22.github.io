<template>
  <div id="navbar">
    <div id="item">
      <a href="#landingImg">
        <h3>HOME</h3>
      </a>
      <div id="line"></div>
    </div>
    <div id="item">
      <a href="#mainAboute">
        <h3>ABOUTE</h3>
      </a>
    </div>
    <div id="item">
      <a href="#mainSkills">
        <h3>SKILLS</h3>
      </a>
    </div>
    <div id="item">
      <a href="#mainProjects">
        <h3>PROJECTS</h3>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  components: {},
  methods: {
    methods: {
      scrollMeTo(refName) {
        var element = this.$refs[refName];
        var top = element.offsetTop;

        window.scrollTo(0, top);
      },
    },
  },
};

// document.getElementById(id).scrollIntoView({
//         behavior: "smooth"
//       });
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#navbar {
  position: absolute;
  top: 45px;
  right: 5%;
}

#item {
  color: white;
  /* text-decoration: underline #5e72eb 5px; */
  float: left;
  margin-left: 40px;
}

h3 {
  margin: 0;
  font-weight: 500;
}

#line {
  width: 150%;
  height: 5px;
  background-color: #5e72eb;
  position: relative;
  left: -23%;
}
</style>

// const primaryColor = Color(0xFF0B0742); // const secondaryColor =
Color(0xFF5E72EB); // const bgColor = Color(0xFF120C6E); // const bodyTextColor
= Color(0xFFF4F1DE);
