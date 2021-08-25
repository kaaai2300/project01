<template>
  <div class='menu-bar'>
    <menu-category class='menu-category'/>
    <menu-category class='menu-category'/>
    <menu-category class='menu-category'/>
  </div>
</template>

<script>
import MenuCategory from './MenuCategory.vue'

export default {
  name: 'menu-bar',
  components: {
    MenuCategory
  }
}
</script>

<style>
.menu-bar {
  display: flex;
  justify-content: center;
  width: 80%;
}
.menu-category {
  margin: 0 25px;
}
</style>
