<script setup>
import { computed } from 'vue'
import Product from '../components/Product.vue'

const props = defineProps()
const id = computed(() => props.productId || props.id || '')
</script>

<template>
  <Product :productId="id" />
</template>
