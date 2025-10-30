<template>
  <div>
    <Header />
    <NuxtPage />
    <Footer />
  </div>
  
</template>

<script setup>
  useSeoMeta({
    title: 'MyMonty Events',
    ogTitle: 'MyMonty Events',
    description: 'This is my amazing site, let me tell you all about it.',
    ogDescription: 'This is my amazing site, let me tell you all about it.',
    ogImage: 'https://example.com/image.png',
    twitterCard: 'summary_large_image',
  })
</script>
