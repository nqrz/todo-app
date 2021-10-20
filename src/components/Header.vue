<template>
  <div class="container">
    <div class="hero">
      <span>
        <h1>{{ msg }}</h1>
        <h3>{{ desc }}</h3>
      </span>
      <Button class="btn"></Button>
    </div>
  </div>
</template>

<script setup>
import Button from './Button.vue'
defineProps({
  msg: String,
  desc: String,
})
</script>

<style scoped>
  .hero {
    display: flex;
    justify-content: space-between;
  }
</style>
