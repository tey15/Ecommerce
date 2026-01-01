<template>
  <section class="welcome">
    <h1>Welcome to the Shop</h1>
    <p>Find your favorite products below.</p>
    <ShowCase />
  </section>
</template>

<script setup>
defineOptions({ name: 'AppTheWelcome' })
import ShowCase from '@/components/ShowCase.vue'
</script>

<style scoped>
.welcome {
  padding: 24px;
  text-align: center;
}
.welcome h1 {
  margin: 0 0 8px;
}
</style>
