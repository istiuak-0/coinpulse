<script setup lang="ts">
import { useHead } from '@unhead/vue';
import DefaultLayout from './core/layouts/Default.layout.vue';

useHead({
  title: 'coinpulse',
  link: [
    {
      rel: 'icon',
      href: '/assets/favicon.ico',
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
