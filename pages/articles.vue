<template>
  <section
    class="max-w-screen-xl px-4 py-8 sm:px-6 sm:py-12 lg:px-8 lg:py-16 container mx-auto"
  >
    <h2 class="text-4xl font-bold text-gray-900 text-center mb-10">Cтатьи</h2>
    <section class="grid grid-cols-1">
      <app-article-card
        class="my-5"
        :watched="5"
        :commentsCount="8"
      ></app-article-card>
      <app-article-card class="my-5" :commentsCount="0"></app-article-card>
      <app-article-card class="my-5" :commentsCount="13"></app-article-card>
    </section>
    <app-pagination></app-pagination>
  </section>
</template>
