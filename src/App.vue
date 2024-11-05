<script setup>
import { ref } from "vue";
import Dialog from "./components/Dialog.vue";
import MainPage from "./components/MainPage.vue";

const showRegisterDialog = ref(true);
const showLoginDialog = ref(false);
</script>

<template>
  <main>
    <MainPage />
  </main>

  <!-- <Dialog v-model="showRegisterDialog"> Registration </Dialog>
  <Dialog v-model="showLoginDialog"> Login </Dialog> -->
</template>

<style scoped></style>
