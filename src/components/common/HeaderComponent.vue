<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav class="flex items-center justify-between p-6 mb-12 bg-white border-b-2">
    <div class="flex items-center">
      <RouterLink to="/" class="text-xl font-bold text-teal-600 mr-4">🌱 TASKUE</RouterLink>
      <div class="flex border-l-2 px-4 items-center gap-3">
        <span>Powered by</span>
        <img src="/images/kinotio-logo-dark.png" alt="Kinotio Logo" class="w-28">
      </div>
    </div>

    <div class="flex items-center justify-center text-gray-600 capitalize">
      <RouterLink
        to="/about"
        class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform hover:border-teal-500 mx-1.5 sm:mx-6"
      >
        About
      </RouterLink>
      <a
        href="https://github.com/kinotio/taskue"
        class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform hover:border-teal-500 mx-1.5 sm:mx-6 cursor-pointer"
        target="_blank"
      >
      <font-awesome-icon :icon="['fab', 'github']" class="w-6 h-6" />
    </a>
    </div>
  </nav>
</template>
