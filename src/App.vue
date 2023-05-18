<script setup>
</script>

<template>
  <div class="logo-container">
    <img alt="Lib13 logo" src="./assets/logo.png" class="logo"/>
  </div>
  <div class="landing">
    <img alt="Vue logo" src="./assets/DHC-landing.png"/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  align-items: center;
  margin-top: 60px;
}
.logo-container {
  background-color: #ffffff; /* Set a background color for the container */
  display: block;
  align-items: center;
  justify-content: center;
}
.logo {
  width: 75px; /* Adjust the width and height as per your requirements */
  filter: brightness(2);
}
.landing img{
  width: 480px;
}
</style>
