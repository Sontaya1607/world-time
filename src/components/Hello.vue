<script setup lang="ts">
  const props = defineProps({
    name: String
  })

  const uppercase = computed(() => props.name.toLocaleUpperCase())
</script>

<template>
  <div text="red 3xl" font="sans">Hello, {{ uppercase }}</div>
  <div i-carbon-brightness-contrast text-5xl text-yellow></div>
</template>
