<template>
  <div class='menu-bar'>
    <v-layout wrap>
      <v-flex xs12 sm6 md4 lg4 v-for='category in menuCategories' :key='category' class='v-flex'>
        <menu-category
          :category='category'
          class='menu-category'
        />
      </v-flex>
    </v-layout>
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
  max-width: 50%;
}
.menu-category {
  margin: 20px auto;
}
</style>
