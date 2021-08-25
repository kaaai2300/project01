<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <v-app id="inspire" dark>
      <router-view/>
    </v-app>
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
  background-color: #1b1d21;
  height: 100%;
  padding: 0 300px;
}
</style>
