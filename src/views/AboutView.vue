<template>
  <div class="about">
    <p class="text-3xl bg-red-100">hello tailwindcss</p>
    <NButton>hello naive-ui</NButton>
  </div>
</template>

<script setup lang="ts">
import { NButton } from 'naive-ui'
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
