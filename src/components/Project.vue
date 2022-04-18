<template>
  <div id="project">
    <p id="title">AnimiListeV2</p>
    <div id="image">
      <p id="description">
        Reprehenderit incididunt dolor consectetur dolore eiusmod. Eiusmod
        laboris laboris aliquip fugiat commodo. Enim do exercitation proident
        enim irure aliqua adipisicing eu eiusmod. gdygyr g Reprehenderit
        incididunt dolor consectetur dolore eiusmod. Eiusmod laboris laboris
        aliquip fugiat commodo. Enim do exercitation proident enim irure aliqua
        adipisicing eu eiusmod. gdygyr g Reprehenderit incididunt dolor
        consectetur dolore eiusmod. Eiusmod laboris laboris aliquip fugiat
        commodo. Enim do exercitation proident enim irure aliqua adipisicing eu
        eiusmod. gdygyr g Reprehenderit incididunt dolor consectetur dolore
        eiusmod. Eiusmod laboris laboris aliquip fugiat commodo. Enim do
        exercitation proident enim irure aliqua adipisicing eu eiusmod. gdygyr g
        Reprehenderit incididunt dolor consectetur dolore eiusmod. Eiusmod
        laboris laboris aliquip fugiat commodo. Enim do exercitation proident
        enim irure aliqua adipisicing eu eiusmod. gdygyr g
      </p>
    </div>
    <!-- <div > -->
    <!-- </div> -->
    <div id="info">
      <span id="language">Flutter</span>
      <span>2021</span>
    </div>
  </div>
</template>

<script>
/* eslint-disable */

export default {
  name: "Project",
  components: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div,
p,
span {
  margin: 0;
  padding: 0;
}

#project {
  width: 250px;
  height: 200px;
  /* background-color: red; */
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  align-items: flex-start;
}

#title {
  font-size: 20px;
  margin-bottom: 8px;
  margin-left: 4px;
}

#image {
  width: 100%;
  height: 68%;
  /* margin: 20px; */
  background-color: black;
  position: relative;
}

#description {
  opacity: 0;
  margin: 8px;
  overflow: hidden;
  display: -webkit-box !important;
  -webkit-line-clamp: 5;
  -webkit-box-orient: vertical;
  white-space: normal;
  text-align: start;
}

#description:hover {
  opacity: 1;
  margin: 8px;
  overflow: hidden;
  display: -webkit-box !important;
  -webkit-line-clamp: 5;
  -webkit-box-orient: vertical;
  white-space: normal;
  text-align: start;
}

#info {
  font-size: 13px;
  margin-top: 6px;
}

#language {
  margin-right: 170px;
  margin-left: 8px;
}
</style>
