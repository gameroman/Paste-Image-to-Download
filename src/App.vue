<script lang="ts" setup>

// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: "Paste Image to Download",
  meta: [
    { name: 'description', content: "Paste any image in your clipboard to download. Privacy friendly." },
    { name: 'og:type', content: 'website' },
    { name: 'og:image', content: '/social.png' },
  ],
})
</script>

<template>
  <RouterView />
</template>
