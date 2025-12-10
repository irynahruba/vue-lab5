<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="max-w-4xl mx-auto">
      <nav class="p-4 bg-gray-100 rounded-b-lg shadow-md flex space-x-4">
        <RouterLink
          to="/"
          class="text-blue-600 hover:text-blue-800 font-medium"
          active-class="text-blue-800 font-bold"
        >
          Home
        </RouterLink>
        <RouterLink
          to="/about"
          class="text-blue-600 hover:text-blue-800 font-medium"
          active-class="text-blue-800 font-bold"
        >
          About
        </RouterLink>
        <RouterLink
          to="/contact"
          class="text-blue-600 hover:text-blue-800 font-medium"
          active-class="text-blue-800 font-bold"
        >
          Contact
        </RouterLink>
      </nav>
    </div>
  </header>

  <main class="max-w-4xl mx-auto mt-5">
    <RouterView />
  </main>
</template>
