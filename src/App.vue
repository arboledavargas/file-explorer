<script setup>
import MainPage from "./pages/mainPage.vue";
</script>

<template>
  <div class="main-container">
    <MainPage></MainPage>
  </div>
</template>

<style scoped>
  .main-container {
    height: 100%;
    width: 100%;
    display: grid;
    place-items: center;

    background-color: var(--ghost-white);
  }
</style>
