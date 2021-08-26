<template>
  <div class='profile'>
    <my-icon/>
    <h1>kaaai</h1>
    <table class='profile-table'>
      <tr>
        <td class='td1'>誕生日</td>
        <td class='td2'>1998年3月2日</td>
      </tr>
      <tr>
        <td class='td1'>出身地</td>
        <td class='td2'>埼玉県</td>
      </tr>
      <tr>
        <td class='td1'>職業</td>
        <td class='td2'>Webエンジニア</td>
      </tr>
      <tr>
        <td class='td1'>趣味</td>
        <td class='td2'>音楽制作</td>
      </tr>
      <!-- <tr>
        <td></td>
        <td></td>
      </tr> -->
    </table>
  </div>
</template>

<script>
import MyIcon from './MyIcon.vue'

export default {
  name: 'profile',
  components: {
    MyIcon
  },
  props: {
  }
}
</script>

<style>
.td1 {
  width: 80px;
  border-bottom: 1px solid orange;
}
.td2 {
  width: 150px;
  text-align: left;
  border-bottom: 1px solid orange;
  padding-left: 10px;
}
.profile-table {
  line-height: 30px;
  margin: 20px auto;
}
</style>
