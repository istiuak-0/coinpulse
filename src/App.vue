<script setup lang="ts">
import { useHead } from '@unhead/vue';
import DefaultLayout from './core/layouts/Default.layout.vue';

useHead({
  title: 'Coin Pulse',
  link: [
    {
      rel: 'icon',
      href: '/favicon.png',
    },
  ],
  meta: [
    {
      name: 'description',
      content: 'Crypto Screener App with built in high Frequency Terminal & Dashboard',
    },
  ],

  htmlAttrs: {
    class: 'dark',
  },
});
</script>
<template>
  <DefaultLayout>
    <RouterView />
  </DefaultLayout>
</template>
