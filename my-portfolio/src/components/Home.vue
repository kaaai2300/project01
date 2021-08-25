<template>
  <div class='main'>
    <profile class='profile'/>
    <menu-bar class='menu-bar'/>
    <!-- <test/> -->
  </div>
</template>

<script>
import MyIcon from './MyIcon.vue'
import Profile from './Profile.vue'
import MenuBar from './MenuBar.vue'

export default {
  name: 'Home',
  components: {
    MyIcon,
    Profile,
    MenuBar
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
* {
  color: aliceblue;
}
.main {
  background-color: #19171d;
  /* background-color: #1b1d21; */
  /* background-color: #000; */
  width: 100%;
  height: 100%;
}
.profile {
  margin-top: 200px;
}
.menu-bar {
  margin: 100px auto 100px auto;
}
</style>
