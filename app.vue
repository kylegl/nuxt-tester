<script setup lang="ts">
const v = ref('test')
</script>

<template>
  <div>
    <VueMacros v-model="v" />
  </div>
</template>
