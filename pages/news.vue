<template>
  <section
    class="max-w-screen-xl px-4 py-8 sm:px-6 sm:py-12 lg:px-8 lg:py-16 container mx-auto"
  >
    <h2 class="text-4xl font-bold text-gray-900 text-center mb-10">Блог</h2>
    <section class="grid grid-cols-1">
      <app-new-card class="my-5"></app-new-card>
      <app-new-card class="my-5"></app-new-card>
      <app-new-card class="my-5"></app-new-card>
    </section>
    <app-pagination></app-pagination>
  </section>
</template>
