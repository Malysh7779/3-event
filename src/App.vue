<script setup>
import Header from "./components/Header.vue";
import Card from "./components/Card.vue";
</script>

<template>
  <Header />
  <div class="desktop">
    <Card />
  </div>
</template>

<style scoped>
.desktop {
  display: grid;
}
</style>
