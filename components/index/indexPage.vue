<template>
  <index-hero></index-hero>
  <section
    class="max-w-screen-xl px-4 py-8 sm:px-6 sm:py-12 lg:px-8 lg:py-16 container mx-auto"
  >
    <h2 class="text-4xl font-bold text-gray-900 text-center mb-10">
      Последние статьи &mdash;
      <router-link to="/articles"
        ><span
          class="text-transparent bg-gradient-to-tr bg-clip-text from-blue-500 via-pink-500 to-red-500 dark:from-sky-300 dark:via-pink-300 dark:to-red-500"
          >Все статьи &rarr;</span
        ></router-link
      >
    </h2>
    <section
      class="grid grid-cols-1 gap-4 sm:grid-cols-2 sm:items-stretch md:grid-cols-3 md:gap-8"
    >
      <app-article-card></app-article-card>
      <app-article-card></app-article-card>
      <app-article-card></app-article-card>
    </section>
  </section>

  <section
    class="max-w-screen-xl px-4 py-8 sm:px-6 sm:py-12 lg:px-8 lg:py-16 container mx-auto"
  >
    <h2 class="text-4xl font-bold text-gray-900 text-center mb-10">
      Новые курсы &mdash;
      <router-link to=""
        ><span
          class="text-transparent bg-gradient-to-tr bg-clip-text from-blue-500 via-pink-500 to-red-500 dark:from-sky-300 dark:via-pink-300 dark:to-red-500"
          >Все курсы &rarr;</span
        ></router-link
      >
    </h2>
    <section
      class="grid grid-cols-1 gap-4 sm:grid-cols-2 sm:items-stretch md:gap-8"
    >
      <index-course-card></index-course-card>
      <index-course-card></index-course-card>
    </section>
  </section>
</template>

<script setup lang="ts">
const isOpen = ref(false)
</script>
