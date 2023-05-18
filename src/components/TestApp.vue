<script setup>
import { defineProps } from 'vue'

const props = defineProps({
  name: String
})

</script>

<template>
    <p>Hello {{ props.name }}</p>
</template>

<style scoped>
p {
    color: red;
}
</style>