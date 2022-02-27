<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'Board',
  meta: [
    { name: 'description', content: 'A board to display some data' },
  ],
})
</script>

<template>
  <router-view />
</template>
