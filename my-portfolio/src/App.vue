<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <v-app id="inspire" dark>
      <v-content>
        <v-container fluid fill-height class="pa-0">
          <v-layout wrap>
            <router-view/>
          </v-layout>
        </v-container>
      </v-content>
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
  font-family: 'RodinNTLGPro-DB', 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #19171d;
}
</style>
