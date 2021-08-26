<template>
  <v-card
    class='menu-category'
    color='#232529'
    hover
    @click='onClick(category.url)'
  >
    <fa-icon :icon='category.icon' size="2x" color="#1da1f2" class='icon'></fa-icon>
    <v-card-text>
      <p class='text'>{{ category.text }}</p>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  name: 'menu-category',
  props: {
    category: {
      type: Object
    }
  },
  methods: {
    onClick: function (url) {
      console.log('click!')
      window.open(url)
    }
  }
}
</script>

<style>
.menu-category {
  width: 190px;
  height: 190px;
}
.icon {
  margin: 20px;
}
.text {
  margin: 10px 0;
}
</style>
