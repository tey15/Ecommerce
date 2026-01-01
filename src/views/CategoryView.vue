<script setup>
import { computed } from 'vue'
import Category from '../components/Category.vue'

const props = defineProps()
const id = computed(() => props.categoryId || props.id || '')
</script>

<template>
  <Category :categoryId="id" />
</template>
