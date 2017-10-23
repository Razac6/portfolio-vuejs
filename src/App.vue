<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style lang="scss">
  @import url("https://fonts.googleapis.com/css?family=Dosis:200,300,400,500,600,700,800&subset=latin-ext");
  @import url("../node_modules/normalize-css/normalize.css");
  @import url("../node_modules/reset-css/reset.css");



  #app {
    font-family: "Dosis", sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
  }

  body {
    margin: 0;
  }

  .row-wbd-centered {
    padding-left: 15px;
    padding-right: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    height: 100vh;
    color: #24262d;
  }
</style>
