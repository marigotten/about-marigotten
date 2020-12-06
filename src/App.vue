<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
</template>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@100;300;400;500;700;900&display=swap');
@import "@/assets/sass/_reset";
@import "@/assets/sass/_mixin";
@import "@/assets/sass/_variables";
html {
  font-size: 62.5%;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  scroll-behavior: smooth;
}

@media screen and (min-width: 768px) {
  html {
    font-size: 68%;
  }
}

body {
  font-family: "Noto Sans JP", sans-serif;
  font-size: 1.6em;
  font-weight: 400;
  line-height: 1.9;
  letter-spacing: 0.1em;
  color: #333333;
  background-color: white;
  text-align: left;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#wrapper {
  max-width: 76.8rem;
  margin: 0 auto;
}

main {
  max-width: 76.8rem;
  margin: 0 auto;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

img {
  width: 100%;
}

</style>
