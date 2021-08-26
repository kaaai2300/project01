<template>
  <div class='menu-bar'>
    <menu-category
      v-for='category in menuCategories'
      :key='category'
      :category='category'
      class='menu-category'
    />
  </div>
</template>

<script>
import MenuCategory from './MenuCategory.vue'

export default {
  name: 'menu-bar',
  components: {
    MenuCategory
  },
  props: {
    menuCategories: {
      type: Object
    }
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
