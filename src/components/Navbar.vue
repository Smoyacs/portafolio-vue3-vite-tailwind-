<script setup>
import { ref } from 'vue'

const navItems = [
  {
    title: "Experiencia",
    label: "experiencia",
    url: "/#experiencia",
  },
  {
    title: "Proyectos",
    label: "proyectos",
    url: "/#proyectos",
  },
  {
    title: "Sobre mí",
    label: "sobre-mi",
    url: "/#sobre-mi",
  },
  {
    title: "Contacto",
    label: "contacto",
    url: "mailto:sebastian.moya.dev@gmail.com",
  },
]
</script>

<template>
  <header class="fixed top-0 z-10 flex items-center justify-center mt-2 w-full">
    <nav class="flex text-sm font-medium rounded-full text-gray-600 dark:text-gray-200 justify-center items-center bg-white/50 dark:bg-gray-800/90 shadow-lg ring-1 ring-white/10 backdrop-blur">
      <a
        v-for="link in navItems"
        :key="link.label"
        class="relative block px-3 py-3 transition hover:text-blue-500 dark:hover:text-blue-500"
        :aria-label="link.label"
        :href="link.url"
      >
        {{ link.title }}
      </a>
    </nav>
  </header>
</template>

