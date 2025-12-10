<template>
  <div class="p-6 max-w-4xl mx-auto">
    <h1 class="text-3xl font-bold mb-6 text-blue-600">Про нас</h1>

    <div class="bg-white rounded-lg shadow-md p-6 mb-6">
      <h2 class="text-2xl font-semibold mb-4 text-gray-800">Наша команда</h2>
      <p class="text-gray-600 mb-4">
        Ми - група студентів, які вивчають веб-розробку з Vue 3 та Tailwind CSS.
      </p>
      <ul class="list-disc pl-5 text-gray-600 mb-4">
        <li class="mb-2">
          <span class="font-semibold">Vue.js 3</span> з Composition API
        </li>
        <li class="mb-2">
          <span class="font-semibold">TypeScript</span> для типізації
        </li>
        <li class="mb-2">
          <span class="font-semibold">Tailwind CSS v4</span> для стилізації
        </li>
        <li class="mb-2">
          <span class="font-semibold">Vite</span> для збірки проєкту
        </li>
      </ul>
    </div>

    <div class="bg-gray-50 rounded-lg shadow-md p-6">
      <h2 class="text-2xl font-semibold mb-4 text-gray-800">Utility-First підхід</h2>
      <p class="text-gray-600 mb-4">
        Tailwind CSS - це utility-first CSS фреймворк, який надає набір низькорівневих класів
        (наприклад, m-4, p-2, flex, text-lg) для побудови дизайну безпосередньо у вашому HTML/Vue-шаблоні.
      </p>
      <div class="bg-green-50 border border-green-200 rounded p-4">
        <p class="text-green-700 font-medium">
          ✅ Успішно інтегровано Tailwind CSS v4 у Vue 3 проєкт!
        </p>
        <p class="text-green-600 text-sm mt-2">
          Всі стилі перенесені з <code>&lt;style scoped&gt;</code> на utility-класи Tailwind
        </p>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
</script>
