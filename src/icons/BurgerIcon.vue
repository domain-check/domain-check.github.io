<template>
  <svg :class fill="currentColor" viewBox="0 0 17 14" xmlns="http://www.w3.org/2000/svg">
    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
  </svg>
</template>
<script setup lang="ts">
const props = defineProps({
  class: {
    type: String,
    required: false
  }
})
</script>