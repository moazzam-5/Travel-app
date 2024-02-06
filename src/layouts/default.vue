<template>
  <v-app :style="{background:$vuetify.theme.themes.light.colors.primary}">
    <DefaultBar />

    <DefaultView />
  </v-app>
</template>

<script setup>
  import DefaultBar from './default/AppBar.vue'
  import DefaultView from './default/View.vue'
</script>
