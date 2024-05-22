<script setup lang="ts">
import { VueQueryDevtools } from '@tanstack/vue-query-devtools'
</script>

<template>
  <div>
    <RouterView />
    <VueQueryDevtools position="right" />
  </div>
</template>
