<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Интерактивный рентген-портал',
  meta: [
    {
      name: 'description',
      content: 'Портал о классической рентгенологии',
    },
  ],
})

useSeoMeta({
  title: 'Интерактивный рентген-портал',
  ogTitle: 'Интерактивный рентген-портал',
  description: 'Портал о классической рентгенологии.',
  ogDescription: 'Портал о классической рентгенологии.',
  // ogImage: 'https://example.com/image.png',
  // twitterCard: 'summary_large_image',
})
</script>
