<script setup lang="ts">
  const props = defineProps({
    name: String
  })

  const uppercase = computed(() => props.name.toLocaleUpperCase())
</script>

<template>
  <div>Hello, {{ uppercase }}</div>
</template>
