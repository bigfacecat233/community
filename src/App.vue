<template>
  <header class="header">
    <NavBar></NavBar>
  </header>
  <router-view></router-view>
</template>

<script setup>
import "./assets/base.css";
import TheIcon from "./components/TheIcon.vue";
import NavBar from "./components/NavBar.vue";
</script>

<style scoped>
.header {
  height: 80px;
  box-shadow: 0px 4px 24px rgb(0, 0, 0, 0.08);
}
</style>
