<template>
  <div class="max-w-2xl px-8 py-4 bg-white rounded-lg shadow-md mx-auto mb-8">
    <div class="flex items-center justify-between">
      <span class="text-sm font-light text-gray-600 dark:text-gray-400"
        >30 октября 2024</span
      >
      <a
        class="px-3 py-1 text-sm font-bold text-gray-100 transition-colors duration-300 transform bg-gray-600 rounded cursor-pointer hover:bg-gray-500"
        tabindex="0"
        role="button"
        >Статус пользователя</a
      >
    </div>

    <div class="mt-2">
      <label
        for="Description"
        class="block text-sm text-gray-500 dark:text-gray-300"
        >Ваш комментарий</label
      >

      <textarea
        placeholder="Комментарий..."
        class="block mt-2 w-full placeholder-gray-400/70 dark:placeholder-gray-500 rounded-lg border border-gray-200 bg-white px-4 h-32 py-2.5 text-gray-700 focus:border-blue-400 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-40 dark:border-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:focus:border-blue-300"
      ></textarea>
    </div>

    <div class="mt-4 flex items-center justify-between">
      <div class="flex items-center">
        <img
          class="hidden object-cover w-10 h-10 mr-4 rounded-full sm:block"
          src="https://images.unsplash.com/photo-1502980426475-b83966705988?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=40&q=80"
          alt="avatar"
        />
        <span
          class="font-bold text-gray-700 dark:text-gray-200"
          tabindex="0"
          role="link"
          >Залетный чел</span
        >
      </div>
      <button
        class="px-6 py-2 font-medium tracking-wide text-white capitalize duration-300 transform rounded-lg focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-80 hover:animate-background bg-gradient-to-r from-red-300 to-purple-600 p-0.5 shadow-xl transition hover:bg-[length:400%_400%] hover:shadow-sm hover:[animation-duration:_4s]"
      >
        Отправить
      </button>
    </div>
  </div>
</template>
