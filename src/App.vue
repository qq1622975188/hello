<template>
  <div id="app">
    <!--    <img src="./assets/logo.png">-->
    <!--    <a href="#/home">主頁</a>-->
    <!--    <a href="#/user">用戶</a>-->
    <router-view/>
  </div>
</template>

<script>

  export default {
    name: 'App'
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
