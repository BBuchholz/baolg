<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'BAOLG',
  meta: [
    { name: 'description', content: 'Builders Association Ov Layered Generalists' },
    {
      name: 'theme-color',
      content: computed(() => isDark.value ? '#00aba9' : '#ffffff'),
    },
  ],
  link: [
    {
      rel: 'icon',
      type: 'image/svg+xml',
      // href: computed(() => preferredDark.value ? '/favicon-dark.svg' : '/favicon.svg'),
      href: '/favicon-32x32.png',
    },
  ],
})
</script>

<template>
  <RouterView />
</template>
