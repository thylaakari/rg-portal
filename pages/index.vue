<template>
  <Head>
    <Title>{{ title }}</Title>
  </Head>
  <div>
    <h1>Homepage</h1>
    <nuxt-link to="/about">О нас</nuxt-link>
  </div>
</template>

<script setup lang="ts">
const title = ref('Главная')
</script>
