<script setup>
import { RouterLink, RouterView } from 'vue-router'
import "./nano-banana.md"
</script>

<template>
  <header>
    <RouterLink to="/guider">Utpost</RouterLink>
  </header>
  <main>
    <RouterView />
  </main>
</template>
