<template>
  <div class="app-container">
    <Header />

    <div class="main-content">
      <SideBar />
      <TaskList />
    </div>

    <Footer />
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import SideBar from './components/SideBar.vue'
import TaskList from './components/TaskList.vue'
</script>

<style scoped>
.app-container {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.main-content {
  display: flex;
  flex: 1;
}
</style>
