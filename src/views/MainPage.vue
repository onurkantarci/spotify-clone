<script setup lang="ts">
import Sidebar from "../components/Sidebar.vue";
import MainContent from "../components/MainContent.vue";
import Footer from "../components/Footer.vue";
</script>

<template>
  <div class="main-container">
    <Sidebar />
    <div class="content-wrapper">
      <MainContent />
    </div>
    <Footer />
  </div>
</template>

<style scoped>
.main-container {
  display: flex;
}

.content-wrapper {
  display: flex;
  height: 90vh;
  padding-left: 75px;
  margin-left: 285px;
  flex-direction: column;
  flex-grow: 1;
}

.content-wrapper > :nth-child(1) {
  flex-grow: 1;
}

.content-wrapper > :nth-child(2) {
  flex-shrink: 0;
}
</style>
