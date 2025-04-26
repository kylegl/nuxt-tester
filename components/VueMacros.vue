<script setup lang="ts">
const {modelValue} = defineModels<{modelValue: ModelOptions<string, {defaultValue: 'tester'}>}>()
</script>

<template>
<div>
  {{ modelValue }}
</div>
</template>
