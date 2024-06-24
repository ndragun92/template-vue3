<template>
  <div class="p-8 text-center">
    <img class="block mx-auto w-12" src="@/assets/logo.svg" alt="Vue Logo" />
    <h1 class="font-bold mt-12 text-center">
      Welcome to Vue 3 Starter Template Kit
    </h1>
    <h2 class="font-semibold mb-2 mt-10">
      Included Modules:
    </h2>
    <ul class="flex flex-col gap-2">
      <li>
        <a
          class="hover:underline text-blue-500"
          href="https://pinia.vuejs.org/getting-started.html"
          target="_blank"
        >pinia</a>
      </li>
      <li>
        <a
          class="hover:underline text-blue-500"
          href="https://tailwindcss.nuxtjs.org"
          target="_blank"
        >
          @nuxtjs/tailwindcss
        </a>
      </li>
      <li>
        <a
          class="hover:underline text-blue-500"
          href="https://iconify.design/docs/icon-components/vue/"
          target="_blank"
        >@iconify/vue</a>
      </li>
      <li>
        <a
          class="hover:underline text-blue-500"
          href="https://vueuse.org/guide/"
          target="_blank"
        >@vueuse/core</a>
      </li>
      <li class="mt-12">
        <a
          class="flex gap-2 items-center justify-center"
          href="https://github.com/ndragun92/template-vue3"
          target="_blank"
        >
          <Icon class="text-[24px]" icon="mdi:github" /> Click here to check GitHub
          Repository
        </a>
      </li>
    </ul>
  </div>
</template>

<script setup lang="ts">
import { Icon } from '@iconify/vue';
</script>