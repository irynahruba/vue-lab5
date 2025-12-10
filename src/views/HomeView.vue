<template>
  <div class="p-6">
    <h1 class="text-3xl font-bold mb-6 text-blue-600">Головна сторінка</h1>

    <div class="bg-white rounded-lg shadow-md p-6 mb-6">
      <h2 class="text-2xl font-semibold mb-4 text-gray-800">Лабораторна робота №5</h2>
      <p class="text-gray-600 mb-4">
        <span class="font-bold">Тема:</span> Інтеграція Tailwind CSS у проєкт Vue 3 та рефакторинг стилів
      </p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-6">
        <div class="bg-blue-50 p-4 rounded-lg border border-blue-200">
          <h3 class="font-bold text-blue-700 mb-2">Мета роботи</h3>
          <p class="text-blue-600 text-sm">
            Набути практичних навичок з інсталяції та конфігурації фреймворку Tailwind CSS
            у проєкті Vue 3 + Vite.
          </p>
        </div>

        <div class="bg-green-50 p-4 rounded-lg border border-green-200">
          <h3 class="font-bold text-green-700 mb-2">Технології</h3>
          <ul class="text-green-600 text-sm list-disc pl-4">
            <li>Vue 3 + Composition API</li>
            <li>TypeScript</li>
            <li>Tailwind CSS v4</li>
            <li>Vite</li>
          </ul>
        </div>
      </div>

      <div class="bg-yellow-50 p-4 rounded-lg border border-yellow-200">
        <h3 class="font-bold text-yellow-700 mb-2">Виконані завдання:</h3>
        <ul class="text-yellow-600 text-sm list-disc pl-4">
          <li>Встановлення Tailwind CSS v4</li>
          <li>Налаштування Vite плагіна</li>
          <li>Рефакторинг компонентів з CSS на Tailwind</li>
          <li>Створення utility-first дизайну</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
</script>
