<template>
  <v-card class='menu-category'>
    <img src="../assets/logo.png" class='icon'>
    <v-card-actions>
      <v-btn>CLICK</v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  name: 'menu-category'
}
</script>

<style>
.menu-category {
  width: 300px;
  height: 350px;
  background-color: antiquewhite;
}
.icon {
  width: 50%;
}
</style>
