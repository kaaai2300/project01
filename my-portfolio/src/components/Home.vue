<template>
  <div class='main'>
    <profile class='profile'/>
    <menu-bar class='menu-bar' :menuCategories='menuCategories'/>
  </div>
</template>

<script>
import MyIcon from './MyIcon.vue'
import Profile from './Profile.vue'
import MenuBar from './MenuBar.vue'
import {Constants} from '../constants/Constants'

export default {
  name: 'Home',
  components: {
    MyIcon,
    Profile,
    MenuBar
  },
  data () {
    return {
      menuCategories: Constants
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
