<template>
  <div class="task-item">
    - {{ text }}
  </div>
</template>

<script setup>
defineProps({
  text: String
})
</script>

<style scoped>
.task-item {
  margin-bottom: 0.5rem;
}
</style>
