<template>
  <article
    class="hover:animate-background rounded-xl bg-gradient-to-r from-green-300 via-blue-500 to-purple-600 p-0.5 shadow-xl transition hover:bg-[length:400%_400%] hover:shadow-sm hover:[animation-duration:_4s]"
  >
    <div class="rounded-[10px] bg-white p-4 sm:p-6">
      <div class="flex items-center">
        <span class="text-xs text-gray-500"> 28 окт 2024 </span>
        <div v-if="watched">
          <span class="text-xs text-gray-500 px-2">&mdash;</span>
          <span class="text-xs text-gray-500">Прочитано {{ watched }} раз</span>
        </div>
        <div>
          <span class="text-xs text-gray-500 px-2">&mdash;</span>
          <span class="text-xs text-gray-500"
            >{{ commentsCount }} комментариев</span
          >
        </div>
      </div>
      <router-link to="article">
        <h3 class="mt-0.5 text-lg font-medium text-gray-900">
          Отличия бронхопневмонии от плевропневмонии на рентгеноскопии легких
          &rarr;
        </h3>
      </router-link>

      <div class="my-4 flex flex-wrap gap-1">
        <span
          class="whitespace-nowrap rounded-full bg-purple-100 px-2.5 py-0.5 text-xs text-purple-600"
        >
          Рентген
        </span>

        <span
          class="whitespace-nowrap rounded-full bg-purple-100 px-2.5 py-0.5 text-xs text-purple-600"
        >
          Скопия
        </span>
      </div>
      <span class="block text-xs text-gray-500"
        >Автор: Ненужон Нахуйжонович, травматолог ЧМ</span
      >
    </div>
  </article>
</template>

<script setup lang="ts">
const props = defineProps({
  watched: Number,
  commentsCount: Number,
})
</script>
