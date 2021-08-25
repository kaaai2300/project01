<template>
  <div class='main'>
    <div class='prof'>
      <img src="../assets/my_icon.png" class='my-icon'>
      <h1>kaaai</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
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
  /* background-color: #000; */
  height: 100%;
}
.prof {
  margin-top: 200px;
}
.my-icon {
  width: 15%;
}
</style>
