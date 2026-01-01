<template>
  <SearchBox />
  <MenuItem />

  <RouterView />
</template>

<script setup>
defineOptions({ name: 'MainLayout' })
import SearchBox from '@/components/SearchBox.vue'
import MenuItem from '@/components/MenuItem.vue'
</script>
