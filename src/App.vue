<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <router-view />
</template>

<style>
html,
body {
  margin: 0;
  padding: 0;
  background-color: #120c6e;
  scroll-behavior: smooth;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin: 0;
  padding: 0;
}

@font-face {
  font-family: "Parisienne";
  src: local("Parisienne"),
    url(./assets/fonts/Parisienne/Parisienne-Regular.ttf) format("truetype");
}
</style>
