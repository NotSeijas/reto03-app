<template>
  <div class="task-list">
    <TaskItem text="TaskItem 1" />
    <TaskItem text="TaskItem 2" />
    <TaskItem text="TaskItem 3" />
  </div>
</template>

<script setup>
import TaskItem from './TaskItem.vue'
</script>

<style scoped>
.task-list {
  flex: 1;
  padding: 1rem;
}
</style>
